# Website Template 3

Responsive multi-page HTML/CSS website template — part of the LadeStack website-template series. Pure static site built with Bootstrap 3, custom CSS, and FontAwesome icon webfonts — zero build step, just open and serve.

## ✨ Features

- 5 ready-to-customize pages: Home, About Us, Services, Our Gallery, Contact Us
- Responsive Bootstrap 3 grid layout for mobile, tablet, and desktop
- Modular CSS: `css/default.css` (theme) + `css/custom.css` (overrides)
- Full FontAwesome icon webfont bundled in `fonts/` (eot, svg, ttf, woff)
- `js/bootstrap.min.js` for off-the-shelf interactive components
- SEO-friendly `sitemap.xml` included
- No build pipeline, no dependencies, no backend

## 📄 Pages included

- `index.html` / `home.html` — Home
- `about-us.html` — About Us
- `services.html` — Services
- `our-gallery.html` — Our Gallery
- `contact-us.html` — Contact Us

## 🛠️ Tech stack

- HTML5
- CSS3 (`default.css`, `custom.css`)
- Bootstrap 3 grid + `bootstrap.min.js`
- FontAwesome icon webfonts

## 🚀 Quick start

```bash
# any static server works
python3 -m http.server 8080
```

Then open <http://localhost:8080/> in a browser. You can also deploy it as-is to GitHub Pages, Cloudflare Pages, Netlify, or any static host.

## 📁 Project structure

```
.
├── index.html            # entry page (copy of home.html)
├── home.html
├── about-us.html
├── services.html
├── our-gallery.html
├── contact-us.html
├── css/                  # default.css, custom.css
├── js/                   # bootstrap.min.js
├── fonts/                # FontAwesome webfonts
└── sitemap.xml
```

## 🎨 Customization

1. Edit placeholder text and sections directly in each HTML file.
2. Tweak theme colours in `css/default.css`; add per-section overrides in `css/custom.css`.
3. Point the contact form at your own backend or form service (currently static markup).

## 🌐 Deployment

Static site — enable GitHub Pages (branch `master`, path `/`) or drag the folder onto any static host.

---

Built by **Girish Lade** — [ladestack.in](https://ladestack.in)

> Part of the **Website-template** series — see the other Website-template repos for layout alternatives.
