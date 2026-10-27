# TOYHOUSE: DON'T GET CAUGHT

A playable first-person 3D horror prototype built with Vite, React, TypeScript, Three.js, React Three Fiber and Rapier.

## Run it

1. Install Node.js 20 or newer.
2. Open a terminal in this folder.
3. Run `npm install`
4. Run `npm run dev`
5. Open the local URL Vite prints (usually `http://localhost:5173`).

For a production build, run `npm run build`, then `npm run preview`.

## Controls

- **WASD** move, **mouse** look (click the game to lock pointer)
- **E** interact / leave hiding spot
- **Shift** sprint, **Ctrl** crouch
- **F** flashlight, **I** inventory, **Esc** pause

## Prototype scope

The project contains a procedural 3D level, toy-like pursuing enemy, item pickups, objectives, hiding spots, exit progression, settings, local save data, and end states. It is a playable first-pass prototype, not a fully QA-tested commercial release. Enemy navigation and player collision are intentionally lightweight approximations; the level geometry and navigation can be expanded in later iterations. All visible assets are generated from original geometry and materials.
