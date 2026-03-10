# DJ Big Cali — Digital Experience & Booking Platform

A premium, high-performance portfolio engineered for a professional DJ, where sophisticated brand identity meets seamless motion design. Built entirely with Vanilla JavaScript, this project leverages robust animation libraries to craft an immersive, rhythmic digital environment without the overhead of heavy SPA frameworks.

## Tech Stack & Architecture

- **Vanilla JS (ES6+)** — Core logic, state management, and video orchestration, purposefully avoiding React or other frameworks to maintain uncompromising performance.
- **GSAP (GreenSock Animation Platform)** — Driving all complex motion choreography, timeline sequencing, and scroll-bound animations.
- **Lenis** — Providing buttery-smooth, hardware-accelerated scroll interpolation.
- **HTML5 & CSS3** — Semantic structure paired with a bespoke, dark-mode-first aesthetic utilizing CSS custom properties for a cohesive design system.

## Signature Features

### GSAP 'Logo Intro' Sequence
A highly choreographed, cinematic preloader that sets the stage before the user even begins scrolling. By leveraging precise GSAP timelines, the logo marks its entrance with custom easing, scaling, and opacity shifts—creating an anticipation-building gateway into the experience.

### Lenis Smooth Scrolling
To ensure the interface feels as fluid as a live mix, Lenis orchestrates the native scroll behavior. This transforms the standard interaction model into a continuous, cinematic glide across the viewport, fundamentally elevating the perceived quality of the site.

### Video Background Parallax
Rich, full-bleed visual assets like `big-cali-turntable-video.mp4` and `dj-caligreen.mp4` serve as the environmental foundation. Using subtle CSS transforms bound to scroll positions, a multi-layered parallax effect is achieved, providing depth and dynamism without sacrificing framerate.

## Code Organization & Motion Strategy

The project’s architecture centers around the **modular use of GSAP timelines and ScrollTrigger orchestration**. Rather than ad-hoc animations scattered across the codebase, motion logic is centralized and sequenced logically. 

- **Timeline Synchronization**: Complex, multi-step animations (like the Logo Intro and Hero section build-outs) are bound to master timelines, ensuring perfect staging and allowing easy pacing adjustments across multiple DOM nodes.
- **ScrollTrigger Orchestration**: Scroll-based reveals and sticky media interactions rely exclusively on `ScrollTrigger`, with specialized configurations to handle iOS address bar shifts and mobile layout recalculations seamlessly.

## Asset Architecture

The platform heavily relies on high-fidelity visual assets, optimized and referenced natively from the root directory:
- **Video Elements**: `big-cali-turntable-video.mp4`, `dj-caliblue.mp4`, `dj-caligreen.mp4`, `dj-caliwedding.mp4`, and `dj-turntable.mp4`.
- **Preload Posters**: `big-cali-turntable-poster.jpg`, `dj-caliblue-poster.jpg`, and `dj-caligreen-poster.jpg` to prevent FOUC (Flash of Unstyled Content) and ensure immediate visual engagement during network loads.
- **Branding Assets**: `DJ-logo1.png` and `DJ-logo2.png`.

## Development & Installation

To experience the platform's motion design exactly as intended, local hosting is required.

1. Clone or download the repository to your local machine.
2. Open the project folder in your preferred code editor (e.g., VS Code).
3. We recommend using the **Live Server** extension:
   - Right-click `index.html` and select **"Open with Live Server"**.
4. The site will launch in your default browser at `http://127.0.0.1:5500/`.

---
*Designed & Developed with uncompromising attention to motion and typography.*
