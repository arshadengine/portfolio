# Arshad Shaikh — Interactive Portfolio

> A modern, high-performance developer portfolio featuring cinematic motion design, fluid typography, and interactive web experiences.

---

## ✨ Features

- **Cinematic Entrance Sequence**:
  - Golden handwritten cursive *"hello"* Lottie animation.
  - Luxury split-screen opening banner with smooth cubic-bezier easing.
  - Staggered hero content entrance.
- **Fluid & Responsive Typography**:
  - Fully responsive layouts powered by CSS `clamp()` formulas for seamless scaling across mobile, tablet, and ultra-wide displays.
- **Reactive Magnetic Cursor**:
  - Custom fluid cursor with dynamic scaling, magnetic snapping on interactive targets, and native cursor suppression on precision pointers.
- **Interactive Narrative & Showcase**:
  - About section highlighting background as Founder, AIML Engineer, and Product Builder.
  - Interactive metrics and capability grid.
  - Project showcase with smooth hover transformations and live demo links.
- **Automated CI/CD**:
  - Continuous deployment to Firebase Hosting via GitHub Actions.

---

## 🛠️ Tech Stack

- **Core**: HTML5, Modern CSS3, Vanilla JavaScript (ES6+)
- **Animation & Motion**: GSAP (GreenSock), ScrollTrigger, Lottie-web
- **Hosting & Infrastructure**: Firebase Hosting, GitHub Actions CI/CD

---

## 🚀 Getting Started

### Local Development

No build step or complex dependencies required. Simply serve the repository using any local web server:

```bash
# Using Python
python -m http.server -d public 8000

# Or using Node.js (npx)
npx serve public
```

Navigate to `http://localhost:8000` in your browser.

---

## 🌐 Deployment

This project is configured for automated deployment to Firebase Hosting:

- Pushing to the `main` branch automatically triggers `.github/workflows/firebase-hosting-merge.yml`.
- Production assets are deployed directly to Firebase Hosting live channel.

---

## 👤 Author

**Arshad Shaikh**
- Founder at [Taskas](https://www.taskas.tech/)
- AIML Engineer & Product Builder
- GitHub: [@arshadengine](https://github.com/arshadengine)
