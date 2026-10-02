# E-Commerce Blueprint SPA

An interactive single-page application that presents a complete technical blueprint for a **Custom Apparel E-Commerce Store**. It is not a shopping site itself — it is a polished, interactive planning/reference document rendered as a web app: architecture, tech stack, feature breakdown, database schema, and API reference, all explorable from a sidebar navigation.

## Features

- **Project Dashboard** — high-level overview of the blueprint, scope, and project metrics
- **Tech Stack Explorer** — the recommended stack, with rationale for each choice
- **Feature Explorer** — browsable catalog of planned store features, organized by category, with per-feature detail views
- **System Architecture** — interactive diagrams of how the store's systems fit together
- **Database Schema** — entity relationships and schema reference for the store's data model
- **API Reference** — endpoint-style reference for the store's backend services
- **Warm neutral UI** — Tailwind CSS utility styling, responsive layout, sidebar navigation

## Tech Stack

- Plain **HTML + CSS + JavaScript** (single self-contained file, no build step)
- **Tailwind CSS** via CDN for styling
- No frameworks, no dependencies, no backend

## Quick Start

No install, no build. Open `index.html` in any modern browser:

```bash
git clone https://github.com/girishlade111/E-Commerce-Blueprint-SPA.git
cd E-Commerce-Blueprint-SPA
# open index.html in your browser, or serve it:
npx serve .
```

## Project Structure

```
E-Commerce-Blueprint-SPA/
├── index.html      # The entire application (markup, styles, data, logic)
└── README.md       # This file
```

Everything lives in one file: the blueprint data, the render functions for each section (`renderDashboard`, `renderTechStack`, `renderFeatureExplorer`, `renderSystemArchitecture`, `renderDatabaseSchema`, `renderApiReference`), and the sidebar navigation that switches between them.

## Deploy Notes

Static site — deploy anywhere that serves static files (GitHub Pages, Netlify, Cloudflare Pages). This repo is live on GitHub Pages.

---

Built by Girish Lade · https://ladestack.in
