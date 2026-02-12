# Charity Water Landing Page

A simple static landing page prototype intended to demonstrate a charity-style site layout.

## Overview

This repository contains a minimal static landing page example. It includes a single `index.html` and an `assets/` folder for images used by the page.

## Contents

- `index.html` — main landing page
- `assets/` — images and media (hero, logo, story images)

## Run locally

Serve the project with any static server. For quick local testing using Python 3:

```bash
python3 -m http.server 8000
# then open http://localhost:8000 in your browser
```

## Development notes

- Place production images inside `assets/`. Filenames used in the page include:
	- `assets/logo.png`
	- `assets/hero-photo.jpg`
	- `assets/story-photo.jpg`
- Keep images optimized for web (JPEG/PNG) and consider multiple sizes for responsiveness.
- Edit `index.html` for copy, layout, and accessibility improvements.

## Git workflow

1. Create a branch for your change: `git checkout -b feature/name`
2. Make edits and test locally
3. Stage and commit: `git add . && git commit -m "Short description"`
4. Push and open a pull request

## Next steps (suggested)

- Optimize images and add `srcset` for the hero image.
- Add simple CI or preview deployment (GitHub Pages or Netlify).

## License

Add a license file if this project will be shared publicly.

