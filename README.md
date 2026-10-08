# Obys Agency — Creative Studio Clone 🎨✨

[![Live Demo](https://img.shields.io/badge/Live%20Demo-GitHub%20Pages-2ea44f?logo=github&logoColor=white)](https://mahisharma29.github.io/Obys-Agency/)
[![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![GSAP](https://img.shields.io/badge/GSAP-88CE02?logo=greensock&logoColor=white)](https://gsap.com/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

A front-end recreation of the creative agency website **Obys Agency**, built to practice advanced web animation and interaction design. The project focuses on immersive typography transitions, custom cursor mechanics, scroll-driven storytelling, and smooth scroll rendering.

> **Disclaimer:** This is a non-commercial learning project. The original design, branding, and concept belong to Obys Agency. This clone is not affiliated with or endorsed by them.

---

## 📑 Table of Contents

- [Live Preview](#-live-preview)
- [Key Features](#-key-features--interactions)
- [Tech Stack](#️-tech-stack--libraries)
- [Repository Structure](#-repository-structure)
- [Getting Started](#-getting-started)
- [Deployment](#-deployment)
- [What I Learned](#-what-i-learned)
- [Known Limitations](#-known-limitations)
- [Roadmap](#-roadmap)
- [Credits](#-credits)
- [Author](#-author)
- [License](#-license)

---

## 🌐 Live Preview

Experience the live deployment directly in your browser:

- **Live Demo:** [https://mahisharma29.github.io/Obys-Agency/](https://mahisharma29.github.io/Obys-Agency/)

> Best viewed on a desktop browser (Chrome, Edge, or Firefox) for the full cursor and scroll experience.

---


## ✨ Key Features & Interactions

- **Immersive Preloader:** Sequential loading counter with an animated typographic introduction.
- **Smooth Inertia Scrolling:** Frictionless page navigation powered by Locomotive Scroll.
- **GSAP & ScrollTrigger Animations:** Timeline-based entrance animations, heading reveals, and scroll-linked effects.
- **Interactive Hover Dynamics:** Custom cursor tracking, image distortion effects, and interactive video reel controls.
- **Editorial Typography:** High-contrast type layout, marquee tickers, and a clear visual hierarchy.
- **Responsive Design:** Layout adapts across modern desktop and mobile browsers.

---

## 🛠️ Tech Stack & Libraries

| Technology | Purpose |
| :--- | :--- |
| **HTML5** | Semantic structure and page layout |
| **CSS3** | Flexbox, Grid, and fluid typography |
| **JavaScript (ES6+)** | DOM handling and event orchestration |
| **GSAP (GreenSock)** | High-performance timeline and interaction animations |
| **ScrollTrigger** | Scroll-driven animation triggers |
| **Shery.js / Three.js** | Image displacement, magnetic effects, and canvas visuals |
| **Locomotive Scroll** | Smooth inertial scrolling |
| **GitHub Pages** | Static hosting and deployment |

---

## 📁 Repository Structure

```text
Obys-Agency/
├── index.html          # Main page markup
├── style.css           # Global styles and responsive rules
├── script.js           # Animations, cursor logic, scroll setup
├── assets/
│   ├── images/         # Project and section images
│   ├── videos/         # Showreel and background videos
│   └── fonts/          # Custom typefaces
├── screenshots/        # README preview images
├── LICENSE
└── README.md
```

<!-- TODO: update the tree above to match your actual files and folders -->

---

## 🚀 Getting Started

### Prerequisites

- A modern web browser
- (Optional) [Node.js](https://nodejs.org/) for running a local server
- (Optional) [VS Code](https://code.visualstudio.com/) with the Live Server extension

### Run Locally

```bash
# 1. Clone the repository
git clone https://github.com/MahiSharma29/Obys-Agency.git

# 2. Move into the project folder
cd Obys-Agency

# 3. Start a local server (pick one)
npx serve .
# or open index.html with the VS Code "Live Server" extension
```

Then open the address shown in the terminal, usually `http://localhost:3000`.

> Some effects (video, canvas, and module scripts) work best through a local server rather than by double-clicking `index.html`.

---

## 📦 Deployment

This site is deployed with **GitHub Pages**.

1. Push the project to a GitHub repository.
2. Go to **Settings → Pages**.
3. Under **Build and deployment**, select **Deploy from a branch**.
4. Choose the `main` branch and the `/ (root)` folder, then click **Save**.
5. After a minute or two, the site is live at `https://mahisharma29.github.io/Obys-Agency/`.

---

## 📚 What I Learned

- Building and sequencing animations with GSAP timelines
- Triggering and scrubbing animations with ScrollTrigger
- Combining smooth scrolling with scroll-based animation without conflicts
- Creating a custom cursor and hover interactions
- Writing responsive layouts without a CSS framework
- Hosting and deploying a static site on GitHub Pages

---

## ⚠️ Known Limitations

- Some animations are simplified compared to the original website.
- Optimized for desktop; certain effects are reduced on touch devices.
- Tested mainly on recent versions of Chrome, Edge, and Firefox.

---

## 🗺️ Roadmap

- [ ] Improve mobile performance and touch interactions
- [ ] Add page transitions between sections
- [ ] Add `prefers-reduced-motion` support for accessibility
- [ ] Optimize image and video sizes for faster loading

---

## 🙌 Credits

- Original design inspiration: [Obys Agency](https://obys.agency/)
- Animation: [GSAP](https://gsap.com/)
- Smooth scrolling: [Locomotive Scroll](https://locomotivemtl.github.io/locomotive-scroll/)
- Effects: [Shery.js](https://github.com/prjctimg/sheryjs) and [Three.js](https://threejs.org/)
- Images, videos, and fonts: _add your sources here_

---

## 👩‍💻 Author

**Mahi Sharma**

- GitHub: [@MahiSharma29](https://github.com/MahiSharma29)

If you found this project helpful or interesting, consider giving it a ⭐!

---

## 📄 License

The source code is released under the [MIT License](LICENSE). The original design, brand, and media assets remain the property of their respective owners.
