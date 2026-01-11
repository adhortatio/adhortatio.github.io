# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Overview

This is the **website repository** for Adhortatio BV, a Dutch holding company focused on AI & Longevity investments. The site is hosted on GitHub Pages at https://adhortatio.nl.

## Repository Structure

```
├── index.html          # Main website (single-page)
├── brand-guide.html    # Brand guidelines documentation
├── CNAME               # Custom domain configuration
└── Brand/
    ├── Turritopsis.jpeg.webp   # Hero image (immortal jellyfish)
    ├── static/                  # Favicons and web manifest
    │   ├── favicon.svg          # Primary favicon (transparent, dark colors)
    │   ├── favicon-16x16.png
    │   ├── favicon-32x32.png
    │   ├── apple-touch-icon.png
    │   ├── android-chrome-*.png
    │   └── site.webmanifest
    ├── _archief/               # Archived materials (gitignored)
    ├── Templates/              # Invoice templates (gitignored)
    ├── Font/                   # Source fonts (gitignored)
    └── LogoAI/                 # Old logo files (gitignored)
```

## Key Information

**Logo**: The hybrid logo combines a triangle shell with a golden ratio spiral inside. Colors are teal (#5ec4c4) and amber (#d4a574). The favicon uses darker variants (#2a8a8a, #b8895a) for visibility on any background.

**Typography**:
- Display: Cormorant Garamond (Google Fonts)
- Body: Outfit (Google Fonts)

**Colors**:
- Void (background): #050506
- Teal: #5ec4c4
- Amber: #d4a574
- Text: #f5f5f5

## Development

No build system - static HTML/CSS. Edit files directly and push to deploy via GitHub Pages.
