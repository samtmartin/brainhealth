# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Repository Overview

This is a brain health research repository focused on cognitive decline prevention. The primary output is `index.md`, a comprehensive evidence-based protocol for delaying/preventing cognitive decline based on medical literature and expert recommendations from Dr. Peter Attia and Dr. Richard Isaacson.

## Repository Structure

- `index.md` - Main protocol document with interventions organized by estimated impact (exercise, target blood levels, sleep, smoking, alcohol, nutrition, vitamins/supplements)
- `_layouts/` - Jekyll layout templates for GitHub Pages
  - `default.html` - Main layout with GitHub-flavored markdown styling and external link handling
- `assets/css/` - Custom stylesheets
  - `style.css` - Responsive layout styling (centered, max-width 800px)
- `_config.yml` - Jekyll/GitHub Pages configuration
- `CNAME` - Custom domain configuration (brainhealth.dev)
- `notes/` - Supporting research notes (gitignored)
- `transcripts/` - Source transcripts (gitignored)

## Content Organization

The protocol is structured hierarchically:

1. **Protocol** - Interventions ranked by impact with evidence citations
2. **Appendix** - Detailed implementation guidance (exercise specifics, target level management strategies, sleep improvement strategies, nutrition patterns)

Each section follows this format:
- Recommendations with emoji indicators (💪 for exercise, 🩸 for blood markers, 💤 for sleep, 🔴 for restrictions, 🟢 for beneficial foods, 💊 for supplements)
- "Why" subsections with research evidence
- "How to use" subsections with actionable guidance
- Numbered source citations linking to studies/content

## Key Content Principles

When editing or adding to this repository:

1. **Evidence-based**: All recommendations must be supported by citations from medical experts or peer-reviewed research
2. **Actionable**: Focus on specific, measurable actions (e.g., "below 95" for fasting glucose, "7.5-8.5 hours" for sleep)
3. **Expert-driven**: Primary sources are Dr. Peter Attia (physician studying healthspan/lifespan) and Dr. Richard Isaacson (preventative neurologist)
4. **Citation format**: Inline citations use [number] with full sources listed at end of each section
5. **Organized by impact**: Protocol sections are ordered by estimated effectiveness, not alphabetically
6. **Caveats included**: When research is inconclusive or controversial, include "Caveats" subsections

## GitHub Pages Hosting

This repository is published to GitHub Pages at https://brainhealth.dev. The site uses:
- Jekyll for static site generation with kramdown markdown processor
- GitHub-flavored markdown CSS for content styling
- Custom responsive layout centered at 800px max-width
- Automatic external link handling (opens in new tabs)

When editing layouts or styles, test changes locally with Jekyll if possible before committing.

## Git Workflow

This repository is version-controlled with git. The main branch is `main`. When making changes, follow standard git practices for commits and pull requests (as noted in the "Changes" section at the end of index.md).
