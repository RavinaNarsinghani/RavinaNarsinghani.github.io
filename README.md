# Ravina Narsinghani - Personal Developer Portfolio

A clean, production-ready developer portfolio for **Ravina Narsinghani**, Python Developer and Odoo Developer.

## Overview

This website is built with semantic HTML5, modern vanilla CSS3, and lightweight vanilla JavaScript. Designed specifically for GitHub Pages hosting with zero build steps, external runtime dependencies, or backend servers.

- **URL:** [https://ravinanarsinghani.github.io/](https://ravinanarsinghani.github.io/)
- **Positioning:** Python Developer | Software Developer | Odoo Developer
- **Location:** Gandhinagar, Gujarat

## Features

- **Technical Dark Theme:** High-contrast charcoal and deep navy palette with restrained cyan accents, designed for developer credibility.
- **Mobile-First & Responsive:** Smoothly adapts across all viewport sizes (mobile, tablet, desktop, and ultrawide).
- **Zero Heavy Dependencies:** Pure vanilla web technologies without bloated frameworks.
- **Resume Integration:** Direct access to `assets/resume/Ravina_Narsinghani_Resume.pdf`.
- **Accessible & Semantic:** Keyboard navigation support, proper ARIA attributes, semantic landmarks, and high contrast ratios.
- **SEO & Social Meta:** Open Graph metadata, responsive meta viewport, and favicon.

## Project Structure

```text
RavinaNarsinghani.github.io/
├── index.html        # Main semantic HTML structure and content
├── style.css         # Custom responsive stylesheet and dark theme
├── script.js         # Vanilla JS: dynamic year, mobile nav, scroll states
├── favicon.svg       # SVG brand monogram favicon
├── README.md         # Documentation and preview guide
└── assets/
    └── resume/
        └── Ravina_Narsinghani_Resume.pdf  # Authoritative resume PDF
```

## Running Locally

To preview the portfolio locally without CORS or local file restrictions:

1. Open a terminal in the project directory:
   ```bash
   cd /home/sevencore/Desktop/RavinaNarsinghani.github.io
   ```
2. Start Python's built-in HTTP server:
   ```bash
   python3 -m http.server 8000
   ```
3. Open your browser and navigate to:
   [http://localhost:8000/](http://localhost:8000/)

## Deployment to GitHub Pages

This repository is designed to be hosted directly on GitHub Pages:

1. Add and commit all files:
   ```bash
   git add .
   git commit -m "feat: complete professional portfolio for Ravina Narsinghani"
   ```
2. Push changes to GitHub:
   ```bash
   git push origin main
   ```
3. In GitHub repository settings under **Pages**, ensure the branch is set to `main` and folder to `/ (root)`. The site will publish automatically at `https://ravinanarsinghani.github.io/`.
