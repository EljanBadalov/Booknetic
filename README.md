## 👨‍💻 Author

**Eljan Badalov**

- **GitHub:** [@EljanBadalov](https://github.com/EljanBadalov)
- **Live Demo:** [Booknetic Landing Page on GitHub Pages](https://eljanbadalov.github.io/Booknetic/)

---

# 📅 Booknetic Landing Page & UI Template

A modern, multi-page, responsive front-end website template built to showcase online appointment booking and business management software features.

[![Live Demo](https://img.shields.io/badge/Live_Demo-GitHub_Pages-2ba640?style=for-the-badge&logo=github)](https://eljanbadalov.github.io/Booknetic/)
[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![Sass](https://img.shields.io/badge/Sass-CC6699?style=for-the-badge&logo=sass&logoColor=white)](https://sass-lang.com/)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)

---

## 🌟 Overview

**Booknetic Frontend** is a feature-rich, multi-page web application concept designed to demonstrate clean web architecture, modular SCSS design patterns, dynamic card carousels, and responsive UI layouts. It includes dedicated landing, FAQ, and Blog pages tailored for SaaS product presentations.

---

## ✨ Key Features

- **Multi-Page Layout:** Complete interface with dedicated **Home (`index.html`)**, **FAQ (`FAQ/faq.html`)**, and **Blog (`blog/blog.html`)** pages.
- **Modular SASS/SCSS Architecture:** Structured partials (`_header.scss`, `_footer.scss`, `_features.scss`, `_integrations.scss`, etc.) for scalable styling.
- **Interactive UI & Carousels:** Dynamic sliders and interactive elements powered by custom vanilla JavaScript (`carousel.js`, `main.js`, `booknetic.js`).
- **Responsive & Pixel-Perfect Design:** Fully optimized across desktop, tablet, and mobile viewport sizes.
- **SVG & Asset Management:** Organized vector icons and media assets for optimized load speed and visual fidelity.

---

## 🛠️ Tech Stack

- **Markup:** HTML5
- **Styling:** CSS3, SCSS (Sass)
- **Scripting:** JavaScript (ES6+)
- **Icons & Assets:** SVG vectors, PNG images
- **Deployment:** GitHub Pages

---

## 📂 Project Structure

```text
Booknetic/
├── .vscode/               # Workspace settings configuration
│   └── settings.json
├── FAQ/                   # FAQ page assets & layout
│   ├── scss/
│   ├── faq.html
│   └── faq.js
├── blog/                  # Blog section assets & layout
│   ├── blog scss/
│   ├── image/
│   ├── blog.html
│   └── blog.js
├── css/                   # Compiled CSS files and sourcemaps
│   ├── blog.css
│   ├── cardSlider.css
│   ├── faq.css
│   └── style.css
├── image/                 # Graphical assets and media files
│   ├── Group 5387.svg
│   └── menu.png
├── linear/                # Vector SVG icon assets
├── scss/                  # Primary SCSS source modules
│   ├── _booknetic.scss
│   ├── _businessTypes.scss
│   ├── _color.scss
│   ├── _customers.scss
│   ├── _faq.scss
│   ├── _features.scss
│   ├── _font.scss
│   ├── _footer.scss
│   ├── _function.scss
│   ├── _group1.scss
│   ├── _header.scss
│   ├── _integrations.scss
│   ├── _nav.scss
│   ├── _reset.scss
│   ├── _testiomonials.scss
│   └── style.scss
├── booknetic.js           # Core interactive page logic
├── carousel.js            # Card slider and carousel functionality
├── main.js                # Main script entry point
├── index.html             # Application homepage entry point
└── README.md              # Project documentation
