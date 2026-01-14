# Willie’s Performance & Fab (Prototype Website)

Live site: https://markkobriger.github.io/willies-site/

This repo contains a simple, fast static website (HTML/CSS/JS) for **Willie’s Performance & Fab**. It’s hosted on **GitHub Pages** and is meant to be easy to update with new photos, services, and contact info.

---

## What’s in this repo

- `index.html` — main page (GitHub Pages looks for this)
- `styles.css` — all styling + theme colors
- `script.js` — small JS for mobile menu
- `hero.jpg` — hero image used on the homepage
- `logo.jpg` — logo used in the header / branding (and can be used as favicon)
- `.github/workflows/` — GitHub Actions / Pages build files (if present)

---

## Quick edits (most common)

### Change images
Replace these files (keep the same names):
- `hero.jpg` (homepage hero image)
- `logo.jpg` (logo)

Tip: keep images reasonably sized so the site loads fast (ideally under ~500KB each).

### Update text
Open `index.html` and edit:
- business name / tagline
- services list
- phone number / address / hours

### Adjust the “theme”
Open `styles.css` and edit the CSS variables near the top (colors, background, buttons).

---

## Local preview (on your computer)

Fastest: double-click `index.html` to open in your browser.

Better (so paths behave like a real site):
```bash
python3 -m http.server 5500
