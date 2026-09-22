# 🏺 Egypt's Digital Museum

> **A responsive, interactive journey through 7,000 years of ancient Egyptian civilization — blending the grandeur of the pharaohs with futuristic digital design.**

Created by **Pahan Bimsara**  
President's College, Minuwangoda  
For **Cybernex'26**

---

## 📖 Overview

**Egypt's Digital Museum** is a single-page web experience that brings the treasures of ancient Egypt to life. It combines historical artifacts, a chronological timeline, and immersive virtual exhibitions within a modern, responsive interface. The design draws inspiration from both ancient Egyptian art (gold, hieroglyphs, cosmic skies) and future technology (glassmorphism, holographic effects, interactive 3D previews).

Built entirely with **HTML, CSS, and vanilla JavaScript**, the site runs in any modern browser without external frameworks or build tools.

---

## ✨ Features

- **Immersive Hero Section** – Animated canvas with floating hieroglyphs and glowing particles, a typewriter effect, and a rotating halo.
- **Interactive Timeline** – Nine historical eras (Predynastic to Roman Egypt) presented as clickable nodes. Each era reveals a detailed panel with key achievements and tags.
- **Artifact Gallery** – A dynamic grid of 12+ artifacts with category filters and a live search bar. Each card features a 3D tilt effect, hover glow, and a holographic scanline animation.
- **3D Artifact Modal** – Click any artifact to open a modal where you can drag to rotate a stylised SVG model and read detailed metadata (material, discovery site, current location).
- **Virtual Exhibitions** – Three large, visually rich cards representing current and upcoming exhibitions, with parallax backgrounds and hover interactions.
- **Smooth Scroll & Reveal Animations** – Sections fade and slide into view as you scroll, powered by `IntersectionObserver`.
- **Animated Counters** – Stats strip counts up to real numbers (120,000+ artifacts, 7,000+ years, etc.) when scrolled into view.
- **Custom Cursor** – A subtle glowing ring and dot follow the mouse (on desktop) for a futuristic feel.
- **Newsletter Form** – Client-side validation with instant feedback.
- **Fully Responsive** – Adapts seamlessly from mobile phones to large desktops, with a hamburger menu on smaller screens.
- **Accessibility & Performance** – Reduced-motion support, semantic HTML, and efficient animations.

---

## 🛠️ Tech Stack

| Technology | Usage |
|------------|-------|
| **HTML5** | Semantic structure, inline SVG for artifacts |
| **CSS3** | Custom properties, Flexbox, Grid, backdrop-filter, animations, media queries |
| **JavaScript (ES6+)** | DOM manipulation, Canvas API, IntersectionObserver, event handling |
| **Google Fonts** | `Cinzel` (display) and `Inter` (body) |

No frameworks, no libraries, no build step — just one self-contained `.html` file.
