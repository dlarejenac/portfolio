# Jerald David Cane — Portfolio Website

A single-page developer portfolio built around a blueprint/schematic visual theme — grid backdrops, crop marks, a title block footer, and an animated "system overview" diagram that maps how I work: developer → modules → stack.

**Live site:** _add your deployed URL here_
**CV:** [View on Google Drive](https://drive.google.com/file/d/1LoQux0az_thcZm4sx9ORawGZr60dvKFl/view?usp=sharing)

---

## About

I'm a web developer specializing in Laravel and Vue.js, focused on the structural side of full-stack work — modular systems, API contracts, and database relationships that hold up as products grow. This site is my portfolio: a snapshot of what I've shipped, the stack I use, and how to reach me.

## Sections

- **Hero** — name, role, and an animated SVG diagram of my typical system architecture (Laravel API ↔ Vue.js frontend)
- **About** — a short summary plus a quick-stats strip (systems shipped, primary framework, frontend of choice)
- **Experience** — role history at Elite Software and Data Security Inc. and Go8 Technology Inc.
- **Stack** — a chip-style legend of tools and technologies I use
- **Contact** — email, LinkedIn, GitHub, and location, laid out like a drafting title block

## Tech Stack

Built as a single static HTML file — no build step required.

- **Markup/Styling:** HTML5, CSS3 (custom properties, CSS Grid/Flexbox)
- **Fonts:** [IBM Plex Mono](https://fonts.google.com/specimen/IBM+Plex+Mono) & [IBM Plex Sans](https://fonts.google.com/specimen/IBM+Plex+Sans) via Google Fonts
- **Interactivity:** Vanilla JavaScript (`IntersectionObserver` for scroll-reveal animations)
- **Design system:** dark theme, blueprint grid background, dashed animated connector lines, monospace labeling throughout

## Design Notes

- Fully responsive — layout collapses gracefully at `860px` and `520px` breakpoints
- Respects `prefers-reduced-motion` by disabling animations for users who need it
- Accessible focus states (`:focus-visible`) on all interactive elements
- Diagram SVG includes an `aria-label` describing its content for screen readers

## Running Locally

No dependencies or build tools needed.

```bash
git clone https://github.com/dlarejenac/<repo-name>.git
cd <repo-name>
# then just open index.html in your browser
```

Or serve it locally:

```bash
python3 -m http.server 8000
# visit http://localhost:8000
```

## Structure

```
.
├── index.html      # entire site — markup, styles, and script in one file
└── README.md
```

## Contact

- **Email:** [cane.jeralddavid@gmail.com](mailto:cane.jeralddavid@gmail.com)
- **LinkedIn:** [linkedin.com/in/jerald-david-cane](https://www.linkedin.com/in/jerald-david-cane/)
- **GitHub:** [@dlarejenac](https://github.com/dlarejenac)
- **Location:** Malabon City, Philippines

---

© 2026 Jerald David Cane
