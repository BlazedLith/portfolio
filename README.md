# Wasiq Amir — Personal Portfolio

CS313: Web Engineering — Lab 3 (HTML Advanced - Personal Portfolio II)

## Structure
```
portfolio/
├── index.html
├── hobbies.html
├── contact.html
├── gallery.html
├── skills.html
├── css/
│   └── style.css
├── images/
│   ├── photo1.jpg … photo6.jpg
└── README.md
```

## What changed from Lab 2
- All inline `<style>` blocks removed; every page links `css/style.css`.
- Per-page main-content width is now handled with `body.page-*` classes instead of duplicated inline rules.
- Header nav, home page cards, hobby list, contact info rows, gallery grid, and skills bars/tags
  were rebuilt using `float` + a reusable `.clearfix` class instead of flexbox, per the lab's
  layout requirement.
- Gallery images moved from hotlinked `picsum.photos` URLs to local files in `images/`.
- Pages renamed to match the required structure (`Home.html` → `index.html`, etc.) and every
  nav link updated accordingly.

## Known placeholder
`images/photo1.jpg` … `photo6.jpg` are generated placeholders (solid color + label), not real
photos. Swap these for actual pictures before submitting — grading will notice stock/placeholder
images in a "personal" gallery.

## Live site
`https://<your-github-username>.github.io/portfolio/` — update after enabling GitHub Pages.
