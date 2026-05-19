# Deployment

This is a static site. The homepage source is `index-v2.html`, and the Materials R&D Studio page is `materials-rd-studio.html`.

## Vercel

Deploy this folder as a static project. `vercel.json` rewrites `/` to `/index-v2.html`.

## Netlify

Deploy this folder as a static site. `netlify.toml` rewrites `/` to `/index-v2.html`.

## GitHub Pages

GitHub Pages does not support the same rewrite behavior. For GitHub Pages, either rename/copy `index-v2.html` to `index.html`, or set the entry link directly to `/index-v2.html`.
