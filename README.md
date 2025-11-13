[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](./LICENSE)


# Psyc101 – Personal Psychology Blog

**Psyc101** is a personal blog built with the [Astro](https://astro.build/) framework, designed to deliver high performance, clean typography, and seamless user experience.  
The project emphasizes accessibility, fast static generation, and maintainable architecture for long-term scalability.

---

## Overview

Psyc101 serves as a digital space to explore and publish essays, reflections, and insights in psychology and human behavior.  
The platform integrates modern frontend technologies to provide an optimal reading experience and smooth transitions between posts.

---

## Key Features

- Built with **Astro 5** for fast, static-first delivery  
- **TailwindCSS** integration for responsive and consistent styling  
- **Svelte components** for dynamic and interactive UI elements  
- **Markdown-based content system** for simple post creation  
- **Expressive Code** support for enhanced syntax highlighting, line numbers, and collapsible code sections  
- **KaTeX** for mathematical expressions  
- **Pagefind** full-text search integration  
- **Automatic RSS feed and sitemap** generation  
- **Swup-based transitions** for SPA-like navigation without sacrificing SEO  
- **One-command new post generator** for streamlined publishing workflow  

---

## Tech Stack

| Layer | Technology |
|--------|-------------|
| Framework | Astro |
| Styling | TailwindCSS + Typography Plugin |
| Interactivity | Svelte |
| Content | Markdown / MDX |
| Search | Pagefind |
| Code Rendering | Expressive Code |
| Type Checking | TypeScript |
| Linting & Formatting | Biome |
| Icons | Iconify |

---

## Getting Started

### Prerequisites
- Node.js 18 or higher  
- pnpm package manager (required by project setup)

### Installation
```bash
pnpm install
```
Development
```bash
pnpm dev
```

Starts the local development server (default at http://localhost:4321
).

Build
```bash
pnpm build
```

Builds the project for production and generates the Pagefind search index.

Preview
```bash
pnpm preview
```

Previews the production build locally.

Lint and Format
```bash
pnpm lint
pnpm format
```
Create a New Post
```bash
pnpm new-post
```
Runs a script to generate a new Markdown file with pre-filled metadata

## License

This project is licensed under the [MIT License](./LICENSE).  
You are free to use, modify, and distribute this project with proper attribution.


