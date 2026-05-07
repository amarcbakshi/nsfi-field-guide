# nSFi · New Social Forms · Year One: Teams

Static single-page site for the New Social Forms Initiative (nSFi). Built on top of Lucas Drummond's typography + color discipline from `ldrummond/new-social-forms-website`, with real Supabase Realtime cursor sharing, a sticky workbook gutter prompt, and a FAQ workbook (localStorage notes).

## Stack

Pure static — HTML, CSS, fonts, SVG. No build step. Realtime cursors over Supabase Realtime channels (publishable key, no auth).

## Local preview

```
python3 -m http.server 8000
# http://localhost:8000
```

## Deploy

Static deploy on Vercel from `main`. Pushes to `main` auto-deploy.
