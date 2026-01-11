# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Overview

This is a **brand assets repository** for Adhortatio BV (Dutch business consultancy). It contains corporate identity materials ("Huisstijl") rather than software code. There is no build system, package manager, or code to compile.

## Repository Structure

```
Huisstijl/
├── Font/              # Brand fonts (Nexa, Titillium Web, Source Sans Pro)
├── LogoAI/            # Logo files and brand specification documents
├── static/            # Web-ready assets (favicons, web fonts)
│   └── fonts/         # WOFF2 fonts: Nexa-Bold, Nexa-Light
├── Templates/         # Invoice and document templates
└── _archief/          # Archived previous brand iteration
```

## Key Assets

**Primary Logo Files** (in `Huisstijl/LogoAI/`):
- `adhortatio Main Logo.svg` - Full logo with slogan
- `adhortatio Without Slogan.svg` - Logo without slogan
- `adhortatio Logo Symbol.svg` - Icon/symbol only

**Web Fonts** (in `Huisstijl/static/fonts/`):
- `Nexa-Bold.woff2`
- `Nexa-Light.woff2`

**Favicons** (in `Huisstijl/static/`):
- Standard set: favicon.ico, favicon-16x16.png, favicon-32x32.png
- Mobile: apple-touch-icon.png, android-chrome-192x192.png, android-chrome-512x512.png

## Permissions

This repository is configured for read-only access. See `.claude/settings.local.json` for the allowed operations (ls, find, tree, file commands only).
