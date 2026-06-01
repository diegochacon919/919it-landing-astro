# 919it Landing

Dark-mode landing page for **919it LLC** — a US-based QA automation consultancy specializing in test frameworks, CI/CD pipelines, and end-to-end quality engineering.

Built with [Astro](https://astro.build).

## Live Site

[https://919it.com](https://919it.com)

## Sections

- **Hero** — brand intro with logo, tagline, and CTA
- **About** — company overview and key stats (10+ years, 4 industries, 15+ platforms)
- **Services** — 6 service cards: Test Automation, CI/CD, Mobile & OTT, API Contracts, Performance, QA Audit
- **Tech Stack** — tools and languages grouped by category
- **Experience** — timeline of roles across banking, streaming, e-commerce, and more
- **Contact** — contact info cards + Formspree-powered form

## Tech

- **[Astro](https://astro.build)** — static site generator
- **CSS** custom properties — dark design system with `#00b4d8` accent
- **Inter** + **JetBrains Mono** (Google Fonts)
- **Formspree** — contact form backend (set your form ID in `ContactForm.astro`)

## Quick Start

```bash
npm install
npm run dev      # http://localhost:4321
```

## Build

```bash
npm run build    # output in ./dist
npm run preview  # preview the build locally
```

## Project Structure

```
src/
├── components/
│   ├── ContactForm.astro
│   ├── Footer.astro
│   └── Navbar.astro
├── layouts/
│   └── BaseLayout.astro
├── pages/
│   └── index.astro
└── styles/
    └── global.css
public/
└── logo.png
```

## Contact Form

The contact form uses Formspree. Update the `FORMSPREE_ID` constant in `src/components/ContactForm.astro:13` with your own Formspree endpoint ID before deploying.

## Design

- **Background:** `#1a202c` (dark slate)
- **Accent:** `#00b4d8` (cyan)
- **Text:** `#f7fafc` (near-white)
- **Max width:** 920px centered container
- **Responsive:** breakpoints at 768px and 480px

## License

&copy; 2026 919it LLC. All rights reserved.
