# Rafid Hasan — Developer Portfolio

A modern, fast, dependency-free personal portfolio site. Built with vanilla HTML, CSS and JavaScript — no build step required.

![preview](https://api.dicebear.com/7.x/avataaars/svg?seed=Rafid)

## ✨ Features

- **Dark / light theme** with `localStorage` persistence and system preference detection
- **Responsive layout** — mobile-first navbar with animated hamburger menu
- **Typewriter hero** text and count-up statistics
- **Scrollspy** navigation that highlights the active section
- **Filterable project grid** with gradient thumbnails (no external images)
- **Animated skill bars** that fill on scroll
- **Experience timeline** and **testimonials**
- **Validated contact form** with inline errors and a `mailto:` handoff
- **Accessibility**: skip link, focus rings, ARIA attributes, `prefers-reduced-motion` support
- **SEO-ready**: meta description, Open Graph tags, inline SVG favicon

## 🚀 Run locally

No dependencies. Just open the file:

```bash
# Option 1 — open directly
open index.html          # macOS
xdg-open index.html      # Linux
start index.html         # Windows

# Option 2 — serve locally (recommended)
python3 -m http.server 5173
# then visit http://localhost:5173
```

Or with Node:

```bash
npx serve .
```

## 🛠️ Customize

All content lives in `index.html`:

1. **Name / brand** — search for `Rafid` and update the logo, hero heading, and meta tags.
2. **Avatar & photos** — replace the DiceBear URLs with your own image paths.
3. **Projects** — edit the `<article class="project">` cards (set `data-category` to `web`, `mobile` or `tools`).
4. **Skills** — change the `data-w` percentages and labels.
5. **Contact** — update `hello@rafid.dev`, phone and social links; the form composes a `mailto:`.

## 🎨 Theming

Colors are defined as CSS variables in `:root` (light) and `[data-theme="dark"]`. Change `--primary` and `--accent` to re-skin the whole site instantly.

## 📄 License

MIT — free to use and adapt.
