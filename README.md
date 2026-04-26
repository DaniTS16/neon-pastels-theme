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
- `theme/assets/css/main.css` — Compiled CSS
- `theme/assets/css/scss/` — SCSS source files

### Config + Schema

- `config/theme.config.json` — Theme instance JSON  
- `schemas/tumblr-theme.schema.json` — JSON Schema validation

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

## Tumblr Option Names

Tumblr requires **no spaces** in option names. All option names use camelCase:

```
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

### Available Option Values

**Booleans:**
- `DarkModeDefault` — Enable dark mode by default
- `EnableLogoAnimation` — Animate the blog title logo
- `ReduceMotion` — Disable all animations (respects system preference)
- `LuvOnlyMode` — Remove legal footer (private use only)

**Color Palette:**
- `Pastel` (default light mode)
- `Peach` (warm light mode)
- `Lilac` (cool light mode)
- `Neon` (dark mode)

**Layout Style:**
- `Single` (default, 42rem width)
- `Wide` (72rem width)
- `Magazine` (72rem, 2-column)

**Motion Preset:**
- `Subtle` (300ms fade-up)
- `Brand` (600ms fade-up, default)
- `Static` (no animations)

**Neon Glow Intensity:**
- `Soft` (minimal glow)
- `Medium` (default)
- `Strong` (intense glow)

**Footer Text:**
- Any custom text (default: "Powered by Tumblr")

---

## Installation

1. Upload `theme/index.html` into Tumblr's theme editor.  
2. Upload preview PNGs when submitting to Theme Garden.  
3. Adjust theme options in the Tumblr customization panel.  
4. For private or portfolio use, enable **LuvOnlyMode** to remove legal footer text.

---

## License

© IRI National d/b/a Luv Media Group.  
Branding is protected and may not be removed except in private mode.
