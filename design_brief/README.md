# Xueyi — Portfolio (static build)

Static site. No build step, no dependencies to install.

## Deploy on Vercel
1. Push this folder to a Git repo (its contents at the repo root).
2. In Vercel: New Project -> import the repo.
3. Framework Preset: **Other**. Build Command: leave empty. Output Directory: leave empty (root).
4. Deploy. `index.html` is served at `/`.

## Files
- `index.html` — the whole page (home + BACCA case study, one document)
- `Portfolio.dc.html` — identical copy; the in-page "back to work" links point at this filename
- `support.js` — runtime that renders the page template
- `image-slot.js` — image placeholder component
- `assets/` — screenshots used by the page

Fonts load from Google Fonts, so the first paint needs a network connection.
