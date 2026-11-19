# Witch of Mountain Winds — eco cosmetics landing page

🌐 **Live site:** [mferaji.github.io/makeup_site-web](https://mferaji.github.io/makeup_site-web/)

[![Deploy to GitHub Pages](https://github.com/MFeraji/makeup_site-web/actions/workflows/deploy.yml/badge.svg)](https://github.com/MFeraji/makeup_site-web/actions/workflows/deploy.yml)

Landing page for an eco cosmetics brand, built with plain HTML and CSS.

## Getting started

```bash
npm install
npm run dev
```

The site opens at http://localhost:8080.

## Scripts

| Command           | Description                                                  |
| ----------------- | ------------------------------------------------------------ |
| `npm run dev`     | Start a local dev server (also available as `npm start`)     |
| `npm run build`   | Copy `index.html`, `css/` and `images/` into `dist/`         |
| `npm run preview` | Build and serve `dist/` at http://localhost:8081             |
| `npm run deploy`  | Build and publish `dist/` to the `gh-pages` branch           |

## Deployment

Every push to `main` automatically deploys the site via
[GitHub Actions](.github/workflows/deploy.yml). You can also deploy manually
with `npm run deploy`.

GitHub Pages must be configured to serve from the `gh-pages` branch
(**Settings → Pages → Source: Deploy from a branch → `gh-pages` / root**).

## Project structure

```
index.html          # page markup
css/                # styles (style.css imports all other files)
  components/       # per-section styles
images/             # images and icons
scripts/build.mjs   # build script used by npm run build
```
