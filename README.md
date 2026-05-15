# Personal Portfolio Website — Static Version

A personal portfolio website built from scratch using HTML5 and CSS3, converted from a PSD design file. This is the **static branch** of the project. A more advanced version built with Nuxt.js and Vue.js is available in the [`nuxt` branch](../../tree/nuxt).

**Live Demo:** https://alice-static.netlify.app

---

## Overview

This project started as a PSD design file and was hand-coded into a fully responsive static website using only HTML and CSS — no frameworks, no dependencies. The goal was to build a clean, fast-loading portfolio with a simple structure that could be hosted anywhere.

After completing the static version, the project was rebuilt in Nuxt.js and Vue.js (see the `nuxt` branch) to add server-side rendering, SEO optimisation, component reusability, and a scalable architecture for future API integration.

---

## Features

- Responsive layout — works on mobile, tablet, and desktop
- Multi-page structure: Home, About, Articles, Videos
- Clean navigation with smooth section linking
- Semantic HTML5 markup
- Pure CSS3 styling — no external UI libraries
- Fast load time — zero JavaScript dependencies
- Deployed on Netlify with continuous deployment from GitHub

---

## Tech Stack

| Layer | Technology |
|---|---|
| Markup | HTML5 |
| Styling | CSS3 |
| Hosting | Netlify |
| Source | PSD design file (original) |

---

## Project Structure

```
/
├── home.html
├── about.html
├── articles.html
├── videos.html
├── style.css
└── img/
    └── (assets)
```

---

## Getting Started

No build tools or dependencies required.

Clone the repo and open `index.html` in any browser.

```bash
git clone https://github.com/AshiqueImran/<repo-name>.git
cd <repo-name>
open index.html
```


---

## Deployment

This branch is deployed on **Netlify** via GitHub integration. Any push to this branch triggers an automatic redeployment.

To deploy your own copy:
1. Fork this repo
2. Connect your fork to Netlify
3. Set publish directory to `/` (root)
4. Deploy

---

## Nuxt/Vue Version

The `nuxt` branch contains a full rebuild of this project using **Nuxt.js** and **Vue.js**, offering:

- Server-side rendering (SSR) for better SEO
- Component-based architecture
- Lighter bundle size through code splitting
- Ready for REST API or headless CMS integration

Switch branches to explore: `git checkout Alice_Nuxt`

---

## Why This Project Exists

This portfolio was built to demonstrate end-to-end frontend ownership — from interpreting a PSD design file to writing semantic markup, handling responsive layout in pure CSS, and deploying a production-ready site. The subsequent migration to Nuxt/Vue shows how the same product evolves when engineering requirements change.

---

## License

MIT — free to use and adapt with attribution.

---

## Contact

**Md Ashique Imran**
[LinkedIn](https://www.linkedin.com/in/ashique-imran/) · [GitHub](https://github.com/AshiqueImran)
