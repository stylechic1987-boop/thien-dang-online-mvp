# THIÊN ĐÀNG ONLINE — 3D Prototype

This is an isolated Three.js prototype. The existing 2D game at the repository root remains unchanged.

## Preview locally
Open `3d/index.html` through a local static web server (for example VS Code Live Server). ES modules loaded from the Three.js CDN generally do not work reliably from a direct `file://` URL.

## Controls
- WASD / arrow keys: move
- Drag the mouse: rotate the follow camera
- Mobile: on-screen directional pad
- Pray / Read: switch the player's quiet activity
- VI / EN: switch interface language

## Current scope
- Procedurally built 3D chapel interior, altar, cross, stained-glass windows and pews
- Player avatar and a small static congregation with subtle idle movement
- Third-person follow camera and mobile movement controls
- Basic prayer / seated-reading interaction states

## Not implemented yet
- Rigged GLB characters and high-quality skeletal animations
- True sit / kneel animation clips
- Multiplayer networking, accounts, server authority or chat
- Persistent quest progression and synchronization with the 2D game

This is an early visual/interaction prototype, not a finished game. The main GitHub Pages deployment remains on `main`; this feature branch is intentionally not deployed automatically.
