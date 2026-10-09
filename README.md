# AstraVale Astrophotography Workshop

An interactive landing and registration portal for the AstraVale Astrophotography Workshop. The platform provides curriculum details, interactive gallery showcases, instructor highlights, and participant enrollment workflows.

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![Three.js](https://img.shields.io/badge/Graphics-Three.js-black?logo=three.js)](https://threejs.org/)
[![Status](https://img.shields.io/badge/Status-Completed-success)](#)

---

## Overview

AstraVale is an educational workshop designed to teach practical astrophotography, covering equipment selection, field acquisition, deep-sky tracking, and image post-processing.

This web application serves as the primary gateway for attendees:
- **Interactive Visuals**: Real-time 3D particle background rendered using Three.js.
- **Curriculum Outline**: Six core learning modules from exposure fundamentals to narrowband stacking.
- **Participant Gallery**: Exhibition of captured celestial targets (lunar, planetary, and deep sky).
- **Registration Flow**: Dynamic modal enrollment form for new applicants.

---

## Tech Stack

- **Graphics & Animation**: Three.js, HTML5 Canvas, CSS animations.
- **Frontend Architecture**: Modular JavaScript (ES6+), HTML5, CSS Grid/Flexbox.
- **Typography & Icons**: Google Fonts (Space Grotesk, Inter).

---

## Directory Structure

```
workshop/
├── index.html                  # Main landing page
├── css/
│   └── style.css               # Design system and responsive layouts
├── js/
│   ├── script.js               # Navigation, modal triggers, and scroll behaviors
│   └── three.min.js            # Three.js library and starfield controller
├── AstraVale*.png              # Branding and high-resolution badges
└── photo_*.jpg                 # Workshop session and gallery assets
```

---

## Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/Adel-333/astro-workshop.git
   cd astro-workshop
   ```

2. Open `index.html` directly in any modern browser, or run a local server:
   ```bash
   npx live-server
   # or
   python -m http.server 3000
   ```

---

## License

This project is open-source under the MIT License.
