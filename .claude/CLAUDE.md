# Staff Engineer Presentation Project

## Project Overview
This is a presentation about staff engineers built using Slidev. The presentation covers what differentiates staff engineers from senior engineers, how they work differently, different archetypes, and the behaviors that lift them above their peers.

## Timing Requirements
- Total session slot: 45 minutes
- Q&A at the end
- Account for potential AV issues/late arrivals at start
- **Target presentation duration: 35-40 minutes**

## Key Files
- `skeleton.md` - Raw content scaffold and notes for the presentation. This is where we develop and refine content before moving it into slides
- `slides.md` - The actual Slidev presentation file (markdown format)
- `tasks.md` - Project task list and workflow tracking
- `.claude/CLAUDE.md` - This file. Project-specific context and instructions

## Task Management
- Follow the plan outlined in `tasks.md`
- Mark tasks as complete with [x] as we finish them
- When new tasks emerge during work, suggest adding them to `tasks.md` in the appropriate phase
- Keep task list updated throughout the project

## Tools and Frameworks

### Package Manager
This project uses **pnpm** (not npm). Always use `pnpm` commands:
- `pnpm install` - install dependencies
- `pnpm run dev` - start dev server
- `pnpm run build` - build for production

### Slidev
Slidev is a developer-friendly presentation tool that creates slides from Markdown files.

**Key documentation:**
- Main library ID for Context7: `/slidevjs/slidev`
- Official docs: https://sli.dev

### Neversink Theme
We use the **neversink** theme (academic/education focused).

**Theme docs:** https://gureckis.github.io/slidev-theme-neversink/

**Available layouts:**
- `cover` - Title slide
- `intro` - Introduction slide
- `default` - Standard content
- `section` - Section divider
- `two-cols-title` - Two columns with title
- `top-title` - Title at top
- `top-title-two-cols` - Top title with two columns
- `side-title` - Title on side
- `quote` - Quote presentation
- `full` - Full-screen content
- `credits` - Attribution slide

**Layout options (in frontmatter):**
- `color:` - Color scheme (e.g., "sky", "navy")
- `align:` - Content alignment (e.g., "lt" for left-top)
- `columns:` - Column width (e.g., "is-6")

**Slots for content:**
- Default slot for main content
- Named slots: `::title::`, `::left::`, `::right::` depending on layout

**Common patterns:**
```markdown
---
layout: cover
---
# Slide Title

---
layout: two-cols-title
columns: is-6
---
:: title ::
# My Title

:: left ::
Left content

:: right ::
Right content
```

**Available components:**
- `<Admonition>` - Highlighted boxes with title and icon
- `<SpeechBubble>` - Configurable speech bubbles
- `<StickyNote>` - Sticky note styled elements
- `<QRCode>` - QR code generator
- `<ArrowDraw>` - Hand-drawn style arrows
- `<ArrowHeads>` - Multiple arrows pointing at a spot
- `<Box>` - Rectangle/box shapes
- `<Line>` - Straight lines
- `<Thumb>` - Thumbs up/down icons
- `<CreditScroll>` - Movie-style scrolling credits

## Development Workflow
1. Develop and refine content in `skeleton.md`
2. Once content is approved, convert sections into slides in `slides.md`
3. Preview with `pnpm run dev`
4. Export final presentation as needed

## Content Development Process
- Discuss each section with Chris individually
- Get explicit approval before adding content to skeleton.md
- Iterate on content structure before converting to slides
