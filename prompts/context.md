# Project Context: ns-linktree

## Overview
This project is a premium, personal branded landing page (Linktree alternative) designed for high-performance delivery via CDN. It prioritizes a high-end visual aesthetic using modern web design principles and a narrative introduction experience.

## Technical Stack
- **Structure**: Semantic HTML5
- **Styling**: Vanilla CSS (CSS3)
- **Aesthetic**: Futuristic Dark Mode with Glassmorphism and Mix-Blend Effects
- **Navigation**: View Transitions API (Cross-document)
- **Assets**: 
  - `assets/profile_photo.jpg`: Real professional profile photo.
  - `assets/background.jpg`: cinematic gradient background.
- **Optimization**: Fully static, `localStorage` for visitor persistence, `requestAnimationFrame` for high-performance typing animations.

## Design Decisions
1. **Modern Editorial Header**: 
   - Uses a split layout on desktop and a stacked layout on mobile.
   - Profile photo is a large circular avatar (`250px`) with a neon glow border.
2. **Glassmorphism**: Link cards and buttons use `backdrop-filter: blur(12px)` and semi-transparent backgrounds.
3. **Cinematic Narrative Intro (`intro.html`)**:
   - **Typewriter Flow**: A story-driven introduction using a custom `requestAnimationFrame` engine for smooth text accumulation.
   - **Visual Build-up**: Background image fades in over 20 seconds.
   - **Vibrancy**: Container uses `mix-blend-mode: plus-lighter` for intense color interaction.
   - **Skip Override**: "Skip »" FAB and final links use `?skipped=1` query parameters to bypass redirection logic even if state sync is delayed.
4. **Visitor Redirection & Persistence**:
   - **Smart Redirection**: `index.html` detects new visitors using `localStorage` timestamps (12-hour window).
   - **Replayability**: A "Replay Intro" link on the main portal allows manual access to the introduction.
5. **View Transitions**: Implemented `@view-transition { navigation: auto; }` with a shared `page-content` name to morph layouts seamlessly between pages.
6. **Background Motion**: 
   - **Panning**: The main background image pans slowly (`bgPan` animation) to create a subtle sense of movement.

## Project Goals
- [x] Create a cinematic narrative intro.
- [x] Implement seamless, hardware-accelerated View Transitions.
- [x] Ensure mobile responsiveness and high-impact typography.
- [x] Prioritize performance with `requestAnimationFrame` and CSS-only backgrounds.

## Repository Structure
- `/index.html`: Main landing page with link portal.
- `/intro.html`: Cinematic typewriter entry experience.
- `/style.css`: Core design system for the main portal.
- `/typewriter.css`: Animation engine and styling for the intro experience.
- `/assets/`: Static branding assets.
- `/prompts/`: Project context and prompt persistence.

## Security & Privacy (Mandatory)
- **Open Source Directive**: This project is intended for public consumption. **You must NOT store sensitive information like API keys, secrets, or private credentials in any part of the project codebase or prompt files.**

## Conversation History (Milestones)
- **Jan 6, 2026**: Project inception.
- **Jan 6, 2026**: Implemented "Modern Editorial" redesign and background motion.
- **Jan 6, 2026**: Built the "Typewriter" narrative intro with scroll-accumulation and fading history.
- **Jan 7, 2026**: Integrated **View Transitions API** for seamless navigation between intro and main portal.
- **Jan 7, 2026**: Implemented `localStorage` visitor logic, "Skip »" FAB, and "Replay Intro" functionality.
- **Jan 11, 2026**: Refined intro visuals (blend modes, 20s background fade) and established open-source security directives.

