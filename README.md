# ns-linktree

A premium, cinematic personal landing page and link portal designed for high-performance delivery. This project was developed as a rapid, same-day update to establish a modern digital footprint with a focus on immersive storytelling and visual excellence.

## Features

- **Narrative Intro**: A story-driven, typewriter-style welcome experience with smooth text accumulation and atmospheric background transitions.
- **Cinematic Visuals**: Modern dark mode aesthetic utilizing glassmorphism, `mix-blend-mode` effects, and hardware-accelerated CSS animations.
- **Seamless Navigation**: Integrated with the **View Transitions API** for fluid, app-like morphing between the introduction and the main portal.
- **Smart Visitor Flow**: Persistent redirection logic using `localStorage` ensures first-time visitors see the story, while returning visitors jump straight to the links.
- **High Performance**: Fully static architecture optimized for CDN caching.

## Tech Stack

- **Core**: Semantic HTML5, Vanilla JS
- **Styling**: Modern CSS3 (Variables, Keyframes, Backdrop-Filters)
- **Animation**: `requestAnimationFrame` for the typing engine; CSS keyframes for background motion.
- **Persistence**: `localStorage` (12-hour visit window).

## Navigation Tips

- **Skip Navigation**: Use the "Skip »" button or `?skipped=1` query parameter to bypass the intro sequence.
- **Replay**: Access the introduction at any time via the "Replay Intro" link on the main portal.

---
*Created as a rapid personal brand evolution project.*
