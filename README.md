# Rajveer Singh — Portfolio

Static site. Everything needed is in this one folder — no build step, no
subfolders, no external requests (fonts, styles and scripts are inlined).

- `index.html` — the whole site
- `Rajveer-Singh-Resume.docx` — the résumé the page links to
- `render.yaml` — Render config

## Deploy on Render

1. Push this folder to GitHub as the repository root.
2. Render: **New → Static Site**, connect the repo.
3. It reads `render.yaml`. Setting it up by hand instead:
   - Build command: leave empty
   - Publish directory: `.`

Every push to the default branch redeploys.
