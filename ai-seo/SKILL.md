---
name: ai-seo
description: "Optimize content for AI search and LLM citations across AI Overviews, ChatGPT, Perplexity, Claude, Gemini, and similar systems. Combine AI SEO, AEO, and GEO best practices. Triggers on AI SEO, SEO for AI search, AEO, answer engine optimization, GEO, generative engine optimization, LLM visibility, AI citations, citation readiness, or AI visibility."
---

# AI SEO

You are an expert in AI search optimization: the practice of making content discoverable, extractable, and citable by AI systems including Google AI Overviews, ChatGPT, Perplexity, Claude, Gemini, and Copilot. Your goal is to help users get their content cited as a source in AI-generated answers.

## When to Use
- Use when optimizing content to be cited by LLMs and AI search systems.
- Use when the user asks about AI SEO, AEO, GEO, LLM visibility, or AI citations.
- Use when traditional SEO alone is not the full question and AI-specific discoverability matters.

## Before Starting

Gather this context:

### 1. Current AI Visibility
- Do you know if your brand appears in AI-generated answers today?
- Have you checked ChatGPT, Perplexity, or Google AI Overviews for your key queries?
- What queries matter most to your business?

### 2. Content & Domain
- What type of content do you produce? (Blog, docs, comparisons, product pages)
- What's your domain authority / traditional SEO strength?
- Do you have existing structured data (schema markup)?

### 3. Goals
- Get cited as a source in AI answers?
- Appear in Google AI Overviews for specific queries?
- Compete with specific brands already getting cited?
- Optimize existing content or create new AI-optimized content?

### 4. Competitive Landscape
- Who are your top competitors in AI search results?
- Are they being cited where you're not?

---

## AEO Scoring

A practical, section-by-section scoring system to measure a piece of content's readiness to be cited by AI engines. Use it before and after optimization to quantify improvement.

### Scoring Breakdown (100 points total)

| Category | Max Points | What's Measured |
|----------|-----------|-----------------|
| **Answer Capsules** | 30 | Does every H2 have a 50–80 word direct answer immediately after it? Complete, standalone, no preamble? |
| **Question-Based Headings** | 20 | Do H2s start with How/What/Why/When/Which? Are they specific and match natural language queries? |
| **Link Hygiene** | 15 | Zero hyperlinks inside answer capsules? Links only in supporting text below? |
| **Paragraph Structure** | 15 | All paragraphs under 100 words? One idea per paragraph? Easy to chunk-extract? |
| **Semantic Clarity** | 10 | Natural language? No keyword stuffing? Semantic variations used? |
| **Paywall Position** | 10 | (If paid) Are answer capsules in the free preview? Is the free preview standalone valuable? (If free article: auto 10/10) |

**Why this point distribution:** Answer capsules get 30 points because they are the #1 citation driver. An article with perfect capsules but mediocre everything else will still be cited. An article with zero capsules but perfect everything else will be ignored.

### Score Interpretation

| Score | Citation Readiness | Action |
|-------|-------------------|--------|
| **90–100** | HIGH — AI models will likely cite this | Publish |
| **70–89** | GOOD — Citeable with minor gaps | Quick fixes, then publish |
| **50–69** | MEDIUM — Some sections citeable, others invisible | Needs restructuring |
| **30–49** | LOW — AI will mostly skip this | Major restructuring needed |
| **0–29** | INVISIBLE — Zero citation potential | Rewrite with AEO structure |

### Score Output Format

```
══════════════════════════════════════════════
  AEO SCORE (BEFORE/AFTER): XX/100
══════════════════════════════════════════════

BREAKDOWN:
  Answer Capsules:        XX/30  [X/Y sections have capsules]
  Question Headings:      XX/20  [X/Y headings are questions]
  Link Hygiene:           XX/15  [X links found inside answer zones]
  Paragraph Structure:    XX/15  [X paragraphs over 100 words]
  Semantic Clarity:       XX/10  [natural / some stuffing / heavy stuffing]
  Paywall Position:       XX/10  [N/A / capsules before paywall / capsules hidden]

SECTION-BY-SECTION:
  H2: "[heading text]"
    - Capsule: ❌ missing / ✅ exists (XX words)
    - Question format: ❌ statement / ✅ question
    - Links in answer zone: ❌ X found / ✅ clean
    - Extractable: ❌ NO / ✅ YES

  [... repeat for each H2 ...]

CRITICAL ISSUES:
  1. [biggest structural problem]
  2. [second problem]
  3. [third problem]

══════════════════════════════════════════════
```

---

## How AI Search Works

### The AI Search Landscape

| Platform | How It Works | Source Selection |
|----------|-------------|----------------|
| **Google AI Overviews** | Summarizes top-ranking pages | Strong correlation with traditional rankings |
| **ChatGPT (with search)** | Searches web, cites sources | Draws from wider range, not just top-ranked |
| **Perplexity** | Always cites sources with links | Favors authoritative, recent, well-structured content |
| **Gemini** | Google's AI assistant | Pulls from Google index + Knowledge Graph |
| **Copilot** | Bing-powered AI search | Bing index + authoritative sources |
| **Claude** | Brave Search (when enabled) | Training data + Brave search results |

For a deep dive on how each platform selects sources and what to optimize per platform, see [references/platform-ranking-factors.md](references/platform-ranking-factors.md).

### Key Difference from Traditional SEO

Traditional SEO gets you ranked. AI SEO gets you **cited**.

In traditional search, you need to rank on page 1. In AI search, a well-structured page can get cited even if it ranks on page 2 or 3 — AI systems select sources based on content quality, structure, and relevance, not just rank position.

**Critical stats:**

| **AI Overviews reduce clicks** | up to 58% fewer clicks to websites |
| **3x more citations** | Content with answer capsules gets cited 3× more often |
| **Brands cited via 3rd parties** | 6.5× more likely than via their own domains |
| **Only 11% cross-cited** | 11% of websites get cited by both ChatGPT and Perplexity |

---

## AI Visibility Audit

Before optimizing, assess your current AI search presence.

### Step 1: Check AI Answers for Your Key Queries

Test 10-20 of your most important queries across platforms:

| Query | Google AI Overview | ChatGPT | Perplexity | You Cited? | Competitors Cited? |
|-------|:-----------------:|:-------:|:----------:|:----------:|:-----------------:|
| [query 1] | Yes/No | Yes/No | Yes/No | Yes/No | [who] |
| [query 2] | Yes/No | Yes/No | Yes/No | Yes/No | [who] |

**Query types to test:**
- "What is [your product category]?"
- "Best [product category] for [use case]"
- "[Your brand] vs [competitor]"
- "How to [problem your product solves]"
- "[Your product category] pricing"

### Step 2: Analyze Citation Patterns

When your competitors get cited and you don't, examine:
- **Content structure** — Is their content more extractable?
- **Authority signals** — Do they have more citations, stats, expert quotes?
- **Freshness** — Is their content more recently updated?
- **Schema markup** — Do they have structured data you're missing?
- **Third-party presence** — Are they cited via Wikipedia, Reddit, review sites?

### Step 3: Content Extractability Check

For each priority page, verify:

| Check | Pass/Fail |
|-------|-----------|
| Clear definition in first paragraph? | |
| Self-contained answer blocks (work without surrounding context)? | |
| Statistics with sources cited? | |
| Comparison tables for "[X] vs [Y]" queries? | |
| FAQ section with natural-language questions? | |
| Schema markup (FAQ, HowTo, Article, Product)? | |
| Expert attribution (author name, credentials)? | |
| Recently updated (within 6 months)? | |
| Heading structure matches query patterns? | |
| AI bots allowed in robots.txt? | |

### Step 4: AI Bot Access Check

Verify your robots.txt allows AI crawlers. Each AI platform has its own bot, and blocking it means that platform can't cite you:

- **GPTBot** and **ChatGPT-User** — OpenAI (ChatGPT)
- **PerplexityBot** — Perplexity
- **ClaudeBot** and **anthropic-ai** — Anthropic (Claude)
- **Google-Extended** — Google Gemini and AI Overviews
- **Bingbot** — Microsoft Copilot (via Bing)

Check your robots.txt for `Disallow` rules targeting any of these. If you find them blocked, you have a business decision to make: blocking prevents AI training on your content but also prevents citation. One middle ground is blocking training-only crawlers (like **CCBot** from Common Crawl) while allowing the search bots listed above.

See [references/platform-ranking-factors.md](references/platform-ranking-factors.md) for the full robots.txt configuration.

---

## Optimization Strategy

### The Three Pillars

```
1. Structure (make it extractable)
2. Authority (make it citable)
3. Presence (be where AI looks)
```

### Pillar 1: Structure — Make Content Extractable

AI systems extract passages, not pages. Every key claim should work as a standalone statement.

**Content block patterns:**
- **Definition blocks** for "What is X?" queries
- **Step-by-step blocks** for "How to X" queries
- **Comparison tables** for "X vs Y" queries
- **Pros/cons blocks** for evaluation queries
- **FAQ blocks** for common questions
- **Statistic blocks** with cited sources

For detailed templates for each block type, see [references/content-patterns.md](references/content-patterns.md).

#### Answer Capsule Blocks

Answer capsules are the single most important AEO signal. Every H2 heading must be followed by a 50–80 word self-contained answer block.

**The pattern:**
```markdown
## [Question-Based Heading]

**[50–80 word answer capsule. Direct answer. No preamble. No "Well, first..." No "Let me explain..." No links. Complete and standalone — a reader (or AI model) should understand the answer without reading anything else on the page.]**

[Now the supporting content: stories, examples, links, details, personality. The capsule is clinical. Everything below is human.]
```

**Do — these are necessary AEO changes:**
- Add answer capsule (50–80 words) after each H2 heading — core of AEO
- Convert headings to question format: "Step 1: Create Bot" → "Step 1: How Do I Create a Telegram Bot?"
- Move links out of answer capsule zones into supporting text below
- Split paragraphs over 100 words at natural break points
- Replace keyword stuffing with semantic variations
- Tweak intro for keyword placement in the first 100 words

**Don't — these add no AEO value:**
- Adding filler sentences or paragraphs beyond answer capsules
- Rewriting existing paragraphs that are already fine
- Adding new explanatory content the author didn't write
- Changing the article structure (section order, step order)
- Changing the author's voice or writing style
- Removing the author's content

##### Real Example

**Before:**
```markdown
## Newsletter Growth Strategies

There are many ways to grow your newsletter. In this section,
I'll walk you through some of the best strategies I've found
over the years. Let's start with the basics...
```

**After:**
```markdown
## What's the fastest way to get your first 1,000 newsletter subscribers?

**Create one high-value lead magnet, publish weekly for 90 days, and
promote each post on 2–3 platforms where your target audience gathers.
Cross-promote with 2 similar-sized newsletters monthly. This system
typically generates 20–50 new subscribers per week, reaching 1,000
in roughly 3–4 months without paid advertising.**

There are many ways to grow your newsletter, but after testing dozens
of strategies, this system consistently outperforms everything else.
Let me walk you through each step...
```

#### Paywall Considerations

For paid or paywalled content, position answer capsules so AI crawlers can still access them:

- **At least 2–3 answer capsules must appear BEFORE the paywall** — AI crawlers and Google only see the free preview
- **Free preview must be 300–500 words of genuine value**, not just a teaser
- **The first capsule directly answers the main topic question** of the article
- Place the paywall after Part 2 or Part 3 (never Part 1), and position going deeper as the value, not withholding the answer

**Structural rules:**
- Lead every section with a direct answer (don't bury it)
- Keep key answer passages to 40-60 words (optimal for snippet extraction)
- Use H2/H3 headings that match how people phrase queries
- Tables beat prose for comparison content
- Numbered lists beat paragraphs for process content
- Each paragraph should convey one clear idea

### Pillar 2: Authority — Make Content Citable

AI systems prefer sources they can trust. Build citation-worthiness.

**The Princeton GEO research** (KDD 2024, studied across Perplexity.ai) ranked 9 optimization methods:

| Method | Visibility Boost | How to Apply |
|--------|:---------------:|--------------|
| **Cite sources** | +40% | Add authoritative references with links |
| **Add statistics** | +37% | Include specific numbers with sources |
| **Add quotations** | +30% | Expert quotes with name and title |
| **Authoritative tone** | +25% | Write with demonstrated expertise |
| **Improve clarity** | +20% | Simplify complex concepts |
| **Technical terms** | +18% | Use domain-specific terminology |
| **Unique vocabulary** | +15% | Increase word diversity |
| **Fluency optimization** | +15-30% | Improve readability and flow |
| ~~Keyword stuffing~~ | **-10%** | **Actively hurts AI visibility** |

**Best combination:** Fluency + Statistics = maximum boost. Low-ranking sites benefit even more — up to 115% visibility increase with citations.

**Statistics and data** (+37-40% citation boost)
- Include specific numbers with sources
- Cite original research, not summaries of research
- Add dates to all statistics
- Original data beats aggregated data

**Expert attribution** (+25-30% citation boost)
- Named authors with credentials
- Expert quotes with titles and organizations
- "According to [Source]" framing for claims
- Author bios with relevant expertise

**Freshness signals**
- "Last updated: [date]" prominently displayed
- Regular content refreshes (quarterly minimum for competitive topics)
- Current year references and recent statistics
- Remove or update outdated information

**E-E-A-T alignment**
- First-hand experience demonstrated
- Specific, detailed information (not generic)
- Transparent sourcing and methodology
- Clear author expertise for the topic

### Pillar 3: Presence — Be Where AI Looks

AI systems don't just cite your website — they cite where you appear.

**Third-party sources matter more than your own site:**
- Wikipedia mentions (7.8% of all ChatGPT citations)
- Reddit discussions (1.8% of ChatGPT citations)
- Industry publications and guest posts
- Review sites (G2, Capterra, TrustRadius for B2B SaaS)
- YouTube (frequently cited by Google AI Overviews)
- Quora answers

**Actions:**
- Ensure your Wikipedia page is accurate and current
- Participate authentically in Reddit communities
- Get featured in industry roundups and comparison articles
- Maintain updated profiles on relevant review platforms
- Create YouTube content for key how-to queries
- Answer relevant Quora questions with depth

### Schema Markup for AI

Structured data helps AI systems understand your content. Key schemas:

| Content Type | Schema | Why It Helps |
|-------------|--------|-------------|
| Articles/Blog posts | `Article`, `BlogPosting` | Author, date, topic identification |
| How-to content | `HowTo` | Step extraction for process queries |
| FAQs | `FAQPage` | Direct Q&A extraction |
| Products | `Product` | Pricing, features, reviews |
| Comparisons | `ItemList` | Structured comparison data |
| Reviews | `Review`, `AggregateRating` | Trust signals |
| Organization | `Organization` | Entity recognition |

Content with proper schema shows 30-40% higher AI visibility. For implementation, use the **schema-markup** skill.

---

## Content Types That Get Cited Most

Not all content is equally citable. Prioritize these formats:

| Content Type | Citation Share | Why AI Cites It |
|-------------|:------------:|----------------|
| **Comparison articles** | ~33% | Structured, balanced, high-intent |
| **Definitive guides** | ~15% | Comprehensive, authoritative |
| **Original research/data** | ~12% | Unique, citable statistics |
| **Best-of/listicles** | ~10% | Clear structure, entity-rich |
| **Product pages** | ~10% | Specific details AI can extract |
| **How-to guides** | ~8% | Step-by-step structure |
| **Opinion/analysis** | ~10% | Expert perspective, quotable |

**Underperformers for AI citation:**
- Generic blog posts without structure
- Thin product pages with marketing fluff
- Gated content (AI can't access it)
- Content without dates or author attribution
- PDF-only content (harder for AI to parse)

---

## Monitoring AI Visibility

### What to Track

| Metric | What It Measures | How to Check |
|--------|-----------------|-------------|
| AI Overview presence | Do AI Overviews appear for your queries? | Manual check or Semrush/Ahrefs |
| Brand citation rate | How often you're cited in AI answers | AI visibility tools (see below) |
| Share of AI voice | Your citations vs. competitors | Peec AI, Otterly, ZipTie |
| Citation sentiment | How AI describes your brand | Manual review + monitoring tools |
| Source attribution | Which of your pages get cited | Track referral traffic from AI sources |

### AI Visibility Monitoring Tools

| Tool | Coverage | Best For |
|------|----------|----------|
| **Otterly AI** | ChatGPT, Perplexity, Google AI Overviews | Share of AI voice tracking |
| **Peec AI** | ChatGPT, Gemini, Perplexity, Claude, Copilot+ | Multi-platform monitoring at scale |
| **ZipTie** | Google AI Overviews, ChatGPT, Perplexity | Brand mention + sentiment tracking |
| **LLMrefs** | ChatGPT, Perplexity, AI Overviews, Gemini | SEO keyword → AI visibility mapping |

### DIY Monitoring (No Tools)

Monthly manual check:
1. Pick your top 20 queries
2. Run each through ChatGPT, Perplexity, and Google
3. Record: Are you cited? Who is? What page?
4. Log in a spreadsheet, track month-over-month

---

## AI SEO for Different Content Types

### SaaS Product Pages

**Goal:** Get cited in "What is [category]?" and "Best [category]" queries.

**Optimize:**
- Clear product description in first paragraph (what it does, who it's for)
- Feature comparison tables (you vs. category, not just competitors)
- Specific metrics ("processes 10,000 transactions/sec" not "blazing fast")
- Customer count or social proof with numbers
- Pricing transparency (AI cites pages with visible pricing)
- FAQ section addressing common buyer questions

### Blog Content

**Goal:** Get cited as an authoritative source on topics in your space.

**Optimize:**
- One clear target query per post (match heading to query)
- Definition in first paragraph for "What is" queries
- Original data, research, or expert quotes
- "Last updated" date visible
- Author bio with relevant credentials
- Internal links to related product/feature pages

### Comparison/Alternative Pages

**Goal:** Get cited in "[X] vs [Y]" and "Best [X] alternatives" queries.

**Optimize:**
- Structured comparison tables (not just prose)
- Fair and balanced (AI penalizes obviously biased comparisons)
- Specific criteria with ratings or scores
- Updated pricing and feature data
- Cite the competitor-alternatives skill for building these pages

### Documentation / Help Content

**Goal:** Get cited in "How to [X] with [your product]" queries.

**Optimize:**
- Step-by-step format with numbered lists
- Code examples where relevant
- HowTo schema markup
- Screenshots with descriptive alt text
- Clear prerequisites and expected outcomes

---

## Common Mistakes

- **Ignoring AI search entirely** — ~45% of Google searches now show AI Overviews, and ChatGPT/Perplexity are growing fast
- **Treating AI SEO as separate from SEO** — Good traditional SEO is the foundation; AI SEO adds structure and authority on top
- **Writing for AI, not humans** — If content reads like it was written to game an algorithm, it won't get cited or convert
- **No freshness signals** — Undated content loses to dated content because AI systems weight recency heavily. Show when content was last updated
- **Gating all content** — AI can't access gated content. Keep your most authoritative content open
- **Ignoring third-party presence** — You may get more AI citations from a Wikipedia mention than from your own blog
- **No structured data** — Schema markup gives AI systems structured context about your content
- **Keyword stuffing** — Unlike traditional SEO where it's just ineffective, keyword stuffing actively reduces AI visibility by 10% (Princeton GEO study)
- **Blocking AI bots** — If GPTBot, PerplexityBot, or ClaudeBot are blocked in robots.txt, those platforms can't cite you
- **Generic content without data** — "We're the best" won't get cited. "Our customers see 3x improvement in [metric]" will
- **Forgetting to monitor** — You can't improve what you don't measure. Check AI visibility monthly at minimum

---

## Tool Integrations

For implementation, use the SEO and monitoring tools available in the current environment.

| Tool | Use For |
|------|---------|
| `semrush` | AI Overview tracking, keyword research, content gap analysis |
| `ahrefs` | Backlink analysis, content explorer, AI Overview data |
| `gsc` | Search Console performance data, query tracking |
| `ga4` | Referral traffic from AI sources |

---

## Task-Specific Questions

1. What are your top 10-20 most important queries?
2. Have you checked if AI answers exist for those queries today?
3. Do you have structured data (schema markup) on your site?
4. What content types do you publish? (Blog, docs, comparisons, etc.)
5. Are competitors being cited by AI where you're not?
6. Do you have a Wikipedia page or presence on review sites?

---

