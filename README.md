# Portfolio_2026

Personal portfolio website for **Dev Bajaniya** — a cybersecurity student and enthusiast.
It's a single-page, dark-themed site built as one self-contained `index.html` file
(inline CSS and vanilla JavaScript, no build step or dependencies).

link -> "https://v0-devbajaniya845.vercel.app/portfolio.html"

![Portfolio screenshot](image.png)

## Sections

- **Hero** — intro with an animated typing effect and a decorative 3D core
- **About** — background and focus areas
- **Experience** — internships and roles
- **Projects** — selected security tools and lab work
- **Certifications** — earned credentials
- **Skills** — tools and technologies
- **Education** — academic timeline
- **Contact** — links to reach out

## Tech

- Plain HTML, CSS custom properties, and vanilla JavaScript — no frameworks or build tooling
- Progressive enhancement: content renders without JS; animations layer on via a `.js-ready` flag
- Accessibility: ARIA labels, `:focus-visible` styles, and `prefers-reduced-motion` support
- SEO/meta: Open Graph tags, `theme-color`, and an inline SVG favicon

## Run locally

No build step is required. Either:

```bash
# open the file directly
open index.html
```

or serve it with any static server, for example:

```bash
npx serve .
# or
python3 -m http.server
```

Then visit the printed local URL.

## Deploy

Because it's fully static, you can host it anywhere that serves static files
(Vercel, GitHub Pages, Netlify, etc.). On Vercel, importing the repo and
deploying with no configuration is enough.

## License

Personal project. Feel free to draw inspiration, but please don't republish the
content (name, experience, and credentials) as your own.
