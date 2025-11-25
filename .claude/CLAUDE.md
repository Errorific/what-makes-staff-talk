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

### Slidev
Slidev is a developer-friendly presentation tool that creates slides from Markdown files.

**Key documentation:**
- Main library ID for Context7: `/slidevjs/slidev`
- Official docs: https://sli.dev
- Key features we're using:
  - Markdown-based slides with `---` separators
  - Frontmatter for slide configuration
  - Built-in layouts (two-cols, center, cover, etc.)
  - Vue components
  - Code highlighting

**Common patterns:**
```markdown
---
layout: cover
---
# Slide Title

---
layout: two-cols
---
# Left Column
::right::
# Right Column
```

## Development Workflow
1. Develop and refine content in `skeleton.md`
2. Once content is approved, convert sections into slides in `slides.md`
3. Preview with `npm run dev` or similar Slidev commands
4. Export final presentation as needed

## Content Development Process
- Discuss each section with Chris individually
- Get explicit approval before adding content to skeleton.md
- Iterate on content structure before converting to slides
