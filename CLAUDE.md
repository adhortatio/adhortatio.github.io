# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Overview

This is the **website repository** for Adhortatio BV, a Dutch holding company focused on AI & Longevity investments. The site is hosted on GitHub Pages at https://adhortatio.nl.

## Repository Structure

```
├── index.html          # Main website (single-page)
├── robots.txt          # Search engine directives
├── CNAME               # Custom domain configuration
├── assets/             # Web-serving files (committed, deployed)
│   ├── Turritopsis.jpeg.webp   # Hero image (immortal jellyfish)
│   ├── fonts/                  # Self-hosted web fonts (GDPR compliant)
│   │   ├── cormorant-garamond-variable.woff2
│   │   ├── cormorant-garamond-italic.woff2
│   │   └── outfit-variable.woff2
│   ├── favicon.svg             # Primary favicon (transparent, dark colors)
│   ├── favicon-*.png           # PNG fallbacks
│   ├── apple-touch-icon.png
│   ├── android-chrome-*.png
│   └── site.webmanifest
└── Brand/              # Private brand materials (fully gitignored, never deployed)
    ├── brand-guide.html
    ├── design-system.md
    ├── _archief/
    ├── Templates/
    └── LogoAI/
```

## Key Information

**Logo**: An equilateral triangle (side ~100) with the largest inscribed golden rectangle (100 x 61.8 scaled by 0.5856, sitting on the base, top corners on the sides) and a golden spiral of quarter arcs inside it (radii 61.8, 38.2, 23.6, 14.6, 9.0, 5.6, turning clockwise: left, top, right, bottom, left, top). Colors are teal (#5ec4c4) and amber (#d4a574); the favicon (any background) uses deep variants (#2a8a8a, #b8895a); light backgrounds and print use #2a8a8a with a deeper amber #a87848 (3.9:1 on white). Two variants:
- *Detailed* (64px and up): full hairline grid + six arcs. Used for apple-touch and android icons.
- *Small* (32px and below): rectangle frame + first four arcs, bolder strokes (triangle 5, spiral 9), no grid. Used for the nav logo, favicon.svg and favicon PNGs.

**Motto**: "Scito quid velis; ne minori cede." (Know what you want; don't settle for less.), displayed only in the symbol circle on the about section (the hero title is its English translation; no second Latin line).

**Typography** (self-hosted, GDPR compliant):
- Display: Cormorant Garamond (variable, 300-600 weights)
- Body: Outfit (variable, 300-500 weights)

**Colors**:
- Void (background): #050506
- Teal: #5ec4c4
- Amber: #d4a574
- Text: #f5f5f5

**Security**:
- Content-Security-Policy via meta tag (no scripts, self-hosted resources only)
- robots.txt disallows /assets/ from crawlers
- `<meta name="robots" content="noindex, nofollow">` keeps the page out of search results (robots.txt must keep allowing `/` so crawlers can see it)
- Brand/ fully gitignored, never deployed

## Development

No build system - static HTML/CSS. Edit files directly and push to deploy via GitHub Pages.

**Owner preferences**: This is a personal investment company. No SEO needed, no social media tags, stay hidden. No KVK number on site.
