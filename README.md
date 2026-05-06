# nSFi · A field guide to team forms

Static single-page site for the New Social Forms Initiative (nSFi) — a research and practice initiative at the MIT Center for Constructive Communication, in cooperation with Google Xi.

**Live:** *(populated after first deploy)*
**Status:** Year One · Teams · Vol. 01 · 2026

## Stack

Pure static — no build step. HTML, CSS, fonts, and SVG logos.

## Local preview

Open `index.html` in a browser, or run a local server:

```
python3 -m http.server 8000
# then visit http://localhost:8000
```

## Deploy

Deploys to Vercel from `main`. No build step needed.

## Files

- `index.html` — the page
- `colors_and_type.css` — design tokens + webfont @font-face
- `fonts/` — UN-11ST and TINY5x3 webfonts
- `logos/` — nSFi avatar and stacked wordmark
- `vercel.json` — clean URLs + cache headers for fonts/logos
