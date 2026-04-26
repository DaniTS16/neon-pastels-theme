# Neon Pastels — Tumblr Theme  

Version: 1.2.0  
Status: Theme Garden Ready  
Brand Owner: IRI National d/b/a Luv Media Group  
Author: Luv Media Group

---

## Overview

Neon Pastels is an accessibility-first Tumblr theme featuring:

- Pastel light mode + neon dark mode  
- Brand-governed motion system  
- WCAG 2.1 AA color contrast  
- Zero JavaScript animation timelines  
- Theme Garden–safe (no external tracking, no JSON parsing)

---

## Included Files

### Theme

- `theme/index.html` — Full Tumblr theme with options  
- `theme/index.static.html` — Static Tumblr theme (no options)  
- `theme/preview.static.html` — Standalone preview page  
- `theme/assets/css/main.css` — Full CSS

### Config + Schema

- `config/theme.config.json` — Theme instance JSON  
- `schemas/tumblr-theme.schema.json` — Validation schema

### Branding + Docs

- `docs/BRANDING.md` — Brand lock rules  
- `docs/STATIC-THEME-NOTES.md` — Notes on static versions  
- `CHANGELOG.md` — Version history

### Previews

- `previews/desktop.png`  
- `previews/tablet.png`  
- `previews/mobile.png`  

(These are placeholder PNGs.)

---

## Tumblr Option Names (Updated)

Tumblr requires **no spaces** in option names:

``` html
DarkModeDefault
EnableLogoAnimation
ReduceMotion
LuvOnlyMode
ColorPalette
LayoutStyle
MotionPreset
NeonGlowIntensity
FooterText
```

These keys are stable, predictable, and Theme Garden–safe.

---

## Installation

1. Upload `theme/index.html` into Tumblr’s theme editor.  
2. Upload preview PNGs when submitting to Theme Garden.  
3. Adjust theme options in the Tumblr customization panel.  
4. For private or portfolio use, enable **LuvOnlyMode** to remove legal footer text.

---

## License

© IRI National d/b/a Luv Media Group.  
Branding is protected and may not be removed except in private mode.
