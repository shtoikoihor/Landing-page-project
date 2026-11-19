# 🚲 BIKE — Landing Page

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![SCSS](https://img.shields.io/badge/SCSS-CC6699?style=flat&logo=sass&logoColor=white)
![BEM](https://img.shields.io/badge/BEM-000000?style=flat&logo=bem&logoColor=white)

A landing page for an electric bike, built from a Figma design with **HTML** and **SCSS** — no frameworks, no JavaScript libraries.
The markup and styles are split into independent **BEM blocks**, so every part of the page can be read, changed and reused on its own.

---

## 🔗 Live Preview

👉 **[Open the landing page](https://shtoikoihor.github.io/Landing-page-project/)**

---

## 🎨 Design Reference

[Figma — BIKE (New Version)](https://www.figma.com/file/NZQAIydtHo5QkINyGLHNcq/BIKE-New-Version?node-id=0%3A1) — design provided by Mate Academy.

---

## 🛠 Technologies Used

| Category | Tools |
|---|---|
| Markup | HTML5 (semantic tags) |
| Styles | SCSS: variables, mixins, nesting |
| Methodology | BEM (block / element / modifier) |
| Layout | Flexbox, CSS Grid, media queries |
| Graphics | SVG icons and images |
| Build | Parcel |
| Code quality | Stylelint, Linthtml |

---

## 📁 Project Structure

```
src/
├── index.html
├── images/              # pictures and SVG icons
└── styles/
    ├── style.scss       # entry point, imports all blocks
    ├── utils/
    │   └── _mixins.scss
    └── blocks/
        ├── _variables.scss
        ├── _page.scss
        ├── _header.scss
        ├── _icon.scss
        └── ...          # one file per page block
```

Each block of the page has its own `.scss` file, and `style.scss` only connects them together.

---

## 🚀 Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/)
- npm

### Installation

```bash
git clone https://github.com/shtoikoihor/Landing-page-project.git
cd Landing-page-project
npm install
```

### Run locally

```bash
npm start
```

Open the URL shown in the terminal (usually `http://localhost:1234`).

### Lint

```bash
npm run lint
```

---

## ✨ Features

- Pixel-perfect layout based on the Figma design
- Responsive design for mobile, tablet and desktop
- Mobile menu with page scroll locked while it is open
- Contact form with styled inputs and buttons
- Hover effects, shadows and smooth transitions
- SVG graphics that stay sharp on any screen
- Reusable SCSS variables and mixins

---

