# Static Theme Notes

This theme bundle includes two static variants designed for different use cases.

---

## 1. index.static.html — Static Tumblr Theme

This version removes all Tumblr dynamic logic, including:

- `{block:Options}`
- `{block:If...}`
- `{select:...}`
- Conditional rendering
- Theme options

All values are hard-coded:

- Palette: Pastel  
- Layout: Single  
- Motion preset: Brand  
- Glow intensity: Medium  

This version is ideal for:

- Tumblr themes that must not expose customization options
- Locked-down branded deployments
- Archival or long-term preservation

---

## 2. preview.static.html — Standalone Preview Page

This file is a pure HTML/CSS preview of the theme, independent of Tumblr.

It is ideal for:

- GitHub Pages demos  
- Portfolio presentations  
- Theme Garden preview links  
- Local testing without Tumblr’s templating engine  

---

## Notes

These static versions are not intended for Theme Garden submission.  
They exist to support development, demos, and brand-controlled deployments.
