# Project Context: ns-linktree

## Overview
This project is a premium, personal branded landing page (Linktree alternative) designed for high-performance delivery via CDN. It prioritizes a high-end visual aesthetic using modern web design principles.

## Technical Stack
- **Structure**: Semantic HTML5
- **Styling**: Vanilla CSS (CSS3)
- **Aesthetic**: Futuristic Dark Mode with Glassmorphism
- **Assets**: 
  - `assets/profile.png`: AI-generated 3D professional avatar.
  - `assets/background.png`: AI-generated abstract geometric gradient background.
- **Optimization**: Fully static, no external dependencies (except Google Fonts for performance caching).

## Design Decisions
1. **Glassmorphism**: Link cards use `backdrop-filter: blur(12px)` and semi-transparent backgrounds to create a layered, premium feel.
2. **Background Motion**: 
   - **Panning**: The main background image pans slowly (`bgPan` animation) to create a subtle sense of movement.
   - **Floating Blobs**: Decorative blurred blobs (`blob-1`, `blob-2`, `blob-3`) migrate across the screen, adding depth and dynamic color shifts.
3. **Animations**: Implemented `fadeInDown` and `fadeInUp` keyframes for a smooth entrance experience and subtle hover transforms on interactive elements.
3. **Typography**: Uses 'Inter' via Google Fonts for a clean, modern look.
4. **Color Palette**:
   - Background: `#0a0b10` (Deep Space Blue)
   - Accents: `#00f2ff` (Cyan Neon), `#7000ff` (Electric Violet)
   - Glass: `rgba(255, 255, 255, 0.05)`

## Project Goals
- [x] Create a mostly static HTML page.
- [x] Prioritize CDN delivery and caching.
- [x] Deliver a "WOW" factor with modern UI design.
- [x] Ensure mobile responsiveness.

## Repository Structure
- `/index.html`: Main entry point.
- `/style.css`: Core design system and animations.
- `/assets/`: Static branding assets.
- `/prompts/`: Conversation and context persistence.

## Conversation History
- **Initial Request**: Project started on Jan 6, 2026. Goal: Create a personal branded landing page similar to Linktree.
- **Design Approval**: User approved "Futuristic Dark Mode" with glassmorphism.
- **Background Motion**: User requested motion for the background; implemented CSS panning and floating animated blobs.
- **Context Request**: User requested a context stewardship document in a `prompts/` directory to retain project knowledge.
