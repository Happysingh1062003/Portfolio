# Sanyal Singh — Personal Portfolio

A hyper-minimalist, brutalist personal portfolio website built from first principles.

## ⚡ Overview
This portfolio is designed to be as fast, lightweight, and frictionless as possible. It is built entirely within a single `index.html` file using pure HTML, Vanilla CSS, and modular Vanilla JavaScript. No build steps, no external frameworks, no bloat.

## 🚀 Features
- **Brutalist / Vibe Coding Aesthetic**: Stark monochrome contrast, distinct hardware-accelerated micro-interactions, monospace typography (`JetBrains Mono`), and raw structural layouts without generic grid components.
- **Zero-Dependency Architecture**: 100% vanilla code. Everything from smooth scrolling to dynamic layout transitions is native.
- **Dynamic GitHub Repository Feed**: Automatically fetches, filters, and displays the top 5 most-starred repositories directly from the GitHub API, using `sessionStorage` caching to optimize load times and prevent rate-limiting.
- **SEO & Social Ready**: Fully configured Open Graph (`og:`) and Twitter Card meta tags for rich link previews across platforms.

## 🛠️ Tech Stack
- **HTML5** (Semantic structure)
- **Vanilla CSS3** (Custom properties, Flex/Grid layouts, 60fps hardware-accelerated keyframe animations)
- **Vanilla JavaScript** (ES6+, Fetch API, Web Storage API)

## 📦 Deployment
Because the entire site is a single static file without any build processes, it can be deployed instantly for free on any static hosting provider.

1. **Vercel / Netlify / Cloudflare Pages**: 
   Simply drag and drop the folder, or link this repository to your account.
2. **GitHub Pages**:
   Enable GitHub Pages in your repository settings and select the `main` branch.

## ✍️ Customization
To update the content, simply open `index.html` in your editor. All text, links, and SVGs are inline and clearly commented (e.g., `<!-- WRITING -->`, `<!-- CONTACT -->`).
