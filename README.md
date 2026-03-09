# 🗂️ Portfolio Website — Inlämningsuppgift 2

A responsive, semantic portfolio website built from scratch using pure HTML5 and CSS3 — no frameworks used.

---

## 📸 Preview

![Portfolio Preview]([screenshot.png](https://teal-mooncake-da6846.netlify.app/))

---

## 🚀 Built With

| Technology | Details |
|---|---|
| HTML5 | Semantic markup — `header`, `aside`, `section`, `article`, `footer` |
| CSS3 | Custom Properties (CSS Variables), Flexbox, Media Queries |
| Font Awesome | Icons via kit (`fa`, `fa-solid`, `fa-brands`) |
| Mobile-first | 6 breakpoints: 500px, 560px, 630px, 750px, 950px, 1400px |
| No frameworks | Pure CSS — no Bootstrap or external UI libraries |

---

## ✅ Features

- **Mobile-first** responsive layout with multiple breakpoints
- **Fixed sidebar** (`aside`) visible on large screens (1400px+), hidden on smaller screens
- **Hamburger dropdown menu** for mobile — CSS hover only, no JavaScript needed
- **CSS Variables** for consistent theming (`--bg-main-content-900`, `--content-color` etc.)
- **Hero section** with image, heading, subheading and CTA button
- **About section** — 3 info cards with hover effects and Font Awesome icons
- **Skills section** — alternating image/text layout using `.item-2 { flex-direction: row-reverse }` — no extra HTML classes
- **Blog section** — 3 articles with image and text, responsive grid
- **Contact form** — styled inputs for name, email and message
- **Fixed scroll-to-top button** (bottom right corner)
- **External CSS only** — zero inline styles
- **Relative units** throughout (`rem`, `%`) — no hardcoded px for layout

---

## 📁 Project Structure

```
portfolio/
├── index.html
├── style.css
├── images/
│   ├── img-hero-section.jpg
│   ├── html5-3384039_1280-removebg-preview.png
│   ├── css-logo-2582747_1280-removebg-preview.png
│   ├── js-b4de205cb6d4e7cad43c2971f780cfd9-removebg-preview.png
│   ├── bootstrap-logo-removebg-preview.png
│   ├── blog-1.jpg
│   ├── blog-2.jpg
│   └── blog-3.jpg
└── README.md
```

---

## 🎨 Color Palette

| Variable | Value | Usage |
|---|---|---|
| `--bg-main-content-900` | `#f2f2fc` | Page background |
| `--bg-white-100` | `#fdf9ff` | Cards, sidebar, header |
| `--text-black-900` | `#302e4d` | Body text |
| `--content-color` | `#ec1839` | Accent — buttons, icons, footer |

---

## 📋 Assignment Requirements

Built as part of the **Webbutveckling** course at GRIT Academy.

| Requirement | Status | Notes |
|---|---|---|
| Mobile-first (3+ breakpoints) | ✅ | 6 breakpoints total |
| Semantic HTML | ✅ | `aside`, `header`, `section`, `article`, `footer` |
| Flexbox layout | ✅ | Used throughout for all layouts |
| Relative units only | ✅ | `rem`, `%` used for layout |
| No inline styles | ✅ | All styles in `style.css` |
| Hero section with CTA | ✅ | Image + h1 + h2 + button |
| 3 info blocks (About) | ✅ | card-1, card-2, card-3 |
| Skills — alternating layout (CSS only) | ✅ | `flex-direction: row-reverse` on `.item-2` |
| Blog section | ✅ | 3 articles with image + text |
| Contact form | ✅ | Name, email, message |
| Footer with contact info + last updated | ✅ | Copyright, social links, date |
| W3C + Jigsaw validation | ✅ | No errors or warnings |
| No CSS framework (VG-level) | ✅ | Pure CSS only |

---

## 💡 What I Learned

- Building a fully responsive layout from scratch without any framework
- Using **CSS Flexbox** for both page-level and component-level layouts
- Implementing a **fixed sidebar** that switches to a mobile header using media queries
- Creating **alternating skill layouts** purely with `flex-direction: row-reverse` — no extra HTML classes needed
- Using **CSS Variables** for consistent, maintainable theming across the whole project
- Writing clean, semantic HTML5 that passes W3C validation

---

## 👤 Author

**Eyad Hussen**  
Webbutveckling med inriktning UX & E-handel  
[LinkedIn](#) · [GitHub](#)
