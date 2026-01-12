# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Overview

This is the **website repository** for Adhortatio BV, a Dutch holding company focused on AI & Longevity investments. The site is hosted on GitHub Pages at https://adhortatio.nl.

## Repository Structure

```
├── index.html          # Main website (single-page)
├── robots.txt          # Search engine directives
├── CNAME               # Custom domain configuration
└── Brand/
    ├── brand-guide.html        # Brand guidelines (local only, gitignored)
    ├── Turritopsis.jpeg.webp   # Hero image (immortal jellyfish)
    ├── static/
    │   ├── fonts/              # Self-hosted web fonts (GDPR compliant)
    │   │   ├── cormorant-garamond-variable.woff2
    │   │   ├── cormorant-garamond-italic.woff2
    │   │   └── outfit-variable.woff2
    │   ├── favicon.svg         # Primary favicon (transparent, dark colors)
    │   ├── favicon-*.png       # PNG fallbacks
    │   ├── apple-touch-icon.png
    │   ├── android-chrome-*.png
    │   └── site.webmanifest
    ├── _archief/               # Archived materials (gitignored)
    ├── Templates/              # Invoice templates (gitignored)
    └── LogoAI/                 # Old logo files (gitignored)
```

## Key Information

**Logo**: The hybrid logo combines a triangle shell with a golden ratio spiral inside. Colors are teal (#5ec4c4) and amber (#d4a574). The favicon uses darker variants (#2a8a8a, #b8895a) for visibility on any background.

**Typography** (self-hosted, GDPR compliant):
- Display: Cormorant Garamond (variable, 300-600 weights)
- Body: Outfit (variable, 300-500 weights)

**Colors**:
- Void (background): #050506
- Teal: #5ec4c4
- Amber: #d4a574
- Text: #f5f5f5

## Development

No build system - static HTML/CSS. Edit files directly and push to deploy via GitHub Pages.
