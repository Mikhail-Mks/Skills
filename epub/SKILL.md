---
name: epub
description: EPUB Ebook Generator. Use when the user wants to create professional EPUB ebooks from Markdown, text, or structured content. Supports chapters, TOC, cover image, and metadata.
---

# EPUB

Professional EPUB ebook generator supporting Markdown to EPUB, multiple chapters, TOC, and cover images.

## Trigger Conditions

- "Create ebook"
- "Make EPUB"
- "Markdown to EPUB"
- "save as epub"
---

## Python Code

```python
import os
from ebooklib import epub

class EpubGenerator:
    def __init__(self, title, author='Unknown', language='zh'):
        self.book = epub.EpubBook()
        self.book.set_title(title)
        self.book.set_language(language)
        self.book.add_author(author)
        self.chapters = []
        
    def add_chapter(self, title, content, filename=None):
        """Add a chapter"""
        if filename is None:
            filename = f'chapter_{len(self.chapters)+1}.xhtml'
        
        chapter = epub.EpubHtml(title=title, file_name=filename)
        chapter.content = f'<h1>{title}</h1>{content}'
        
        self.book.add_item(chapter)
        self.chapters.append(chapter)
        return chapter
    
    def add_markdown_chapters(self, markdown_content):
        """Split markdown into chapters"""
        sections = markdown_content.split('\n# ')
        
        for i, section in enumerate(sections):
            if not section.strip():
                continue
            
            lines = section.split('\n')
            title = lines[0].replace('#', '').strip()
            content = '<br>'.join(lines[1:])
            
            self.add_chapter(title, content)
    
    def add_cover(self, image_path):
        """Add cover image"""
        with open(image_path, 'rb') as f:
            cover_image = f.read()
        
        self.book.set_cover('cover.jpg', cover_image)
    
    def set_toc(self):
        """Generate table of contents"""
        self.book.toc = self.chapters
        
        # Add navigation
        self.book.add_item(epub.EpubNcx())
        self.book.add_item(epub.EpubNav())
    
    def add_spine(self):
        """Set reading order"""
        self.book.spine = ['nav'] + self.chapters
    
    def save(self, output_path):
        """Save EPUB file"""
        self.set_toc()
        self.add_spine()
        
        epub.write_epub(output_path, self.book, {})
        return output_path

# Example
gen = EpubGenerator('My Book', author='Author Name')
gen.add_chapter('Chapter 1', '<p>Content here...</p>')
gen.add_chapter('Chapter 2', '<p>More content...</p>')
gen.save('output.epub')
```
