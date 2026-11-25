# Bashar Reda — Graphic Designer Portfolio

Static portfolio website (HTML/CSS/JS + optimized WebP images). No build step, no dependencies except Google Fonts.

## Live site
Deploy with GitHub Pages and the site will be available at `https://<username>.github.io/<repo>/`
(or `https://<username>.github.io` if the repo is named `<username>.github.io`).

## Files
| File | Purpose |
|------|---------|
| `index.html` | The website (~85 KB) |
| `assets/` | Optimized WebP images, lazy-loaded (~6 MB total) |
| `README.md` | This file |

## Deploy on GitHub Pages
1. Create a new repository (e.g. `basharreda.github.io`).
2. Upload `index.html`, the `assets` folder and `README.md` to the `main` branch (Add file → Upload files, or GitHub Desktop / `git push` if the browser upload is slow).
3. Settings → Pages → Source: **Deploy from a branch** → Branch: `main` / `(root)` → Save.
4. Wait 1–2 minutes, then open the site URL.

## Sections
Hero · Clients · Experience · Skills · Portfolio (Social Media, Print Design, Branding, Presentation Design, Illustrations, Typography, Play Store Screens*) · Education · Contact

\* Play Store Screens tab is currently empty.

## Features
- Stacked sliding panels on scroll (desktop), normal scrolling on mobile
- Floating avatar with cursor-follow tilt
- Scroll-linked headline reveal, marquee image rows, stacked portfolio category cards
- Image lightbox and slide-by-slide presentation viewer
- Custom cursor (desktop)

## Editing notes
- Portfolio images are referenced from JS arrays inside `index.html` (files in `assets/`): `socialData`, `printData`, `typographyData`, `illustrationData`, `presentationDecks`.
- Social Media and Illustrations grids exist in both HTML and JS; keep the item count and order identical when adding images.
- Always upload `assets/` together with `index.html`.

## Contact
Bashar Reda — basharreda25@gmail.com — +20 120 416 9861 — Cairo, Egypt

---

## بالعربي (مختصر)
الموقع = `index.html` + فولدر `assets` (الصور). ارفعهم مع بعض على GitHub في repository جديد، ثم من Settings → Pages اختار branch `main` وهيشتغل على رابط `github.io` بعد دقيقة أو اتنين.
