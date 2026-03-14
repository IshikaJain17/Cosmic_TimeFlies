# COSMOS - Space History and Missions

Production-ready interactive 3D space exploration website featuring NASA, ISRO, and SpaceX/Elon Musk milestones, mission archives, and ongoing projects.
https://github.com/IshikaJain17/Cosmic_TimeFlies/actions/runs/23095272001

## Features

- Immersive 3D animated background (Three.js)
- Scroll-based motion effects (GSAP)
- Searchable milestones and projects
- Official source links for missions and agencies
- Mobile-responsive UI
- SEO, Open Graph, Twitter cards, structured data
- PWA manifest support

## Run Locally

This is a static site. You can run it with any local server.

### Option 1: VS Code Live Server

Open `index.html` with Live Server.

### Option 2: Python

```bash
python -m http.server 8080
```

Then open `http://localhost:8080`.

## Deployment

This repository includes a GitHub Actions workflow that deploys to GitHub Pages automatically on push to `main`.

- Workflow: `.github/workflows/deploy-pages.yml`
- Site URL: `https://ishikajain17.github.io/Cosmic_TimeFlies/`

## Production Files

- `index.html` - main application
- `site.webmanifest` - PWA metadata
- `favicon.svg` - site icon
- `robots.txt` - crawler directives
- `sitemap.xml` - URL discovery
- `.nojekyll` - disable Jekyll processing on Pages

## Notes

Some external media is loaded from official NASA/ISRO/SpaceX pages. If a source image URL changes, the card still works and links remain functional.
