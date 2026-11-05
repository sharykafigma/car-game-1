# STREET LEGENDS: RACING WORLD

A playable browser-based 3D racing game foundation built with HTML, CSS, JavaScript and Three.js.

## Run
1. Extract the ZIP.
2. Open a terminal in this folder.
3. Run `python -m http.server 8000`
4. Open `http://localhost:8000` in Chrome, Edge or Firefox.

A local web server is required because the game uses JavaScript modules. Three.js is loaded from jsDelivr at runtime, so an internet connection is required on first load.

## Controls
- W / Up: accelerate
- S / Down: brake and reverse
- A / Left and D / Right: steer
- Space: handbrake / drift
- Shift: nitro
- C: cycle camera
- Esc: pause
- Mobile: on-screen steering, gas, brake and nitro controls

## Included playable systems
- Procedural Three.js 3D city scene and drivable vehicle
- Arcade vehicle handling, steering, reverse, handbrake drift and nitro
- Chase, close and hood camera views
- Quick race, career event, free roam, drift zone, time trial and drag modes
- AI traffic/rivals for race modes
- Garage vehicle selection, paint color, engine upgrades and spoiler toggle
- Car dealership with cash purchases
- HUD, pause, results, profile, achievements and settings
- LocalStorage save for money, cars, upgrades, settings and progression

## Scope note
This is a self-contained playable prototype with procedural geometry rather than a commercial asset pack. It does not include online multiplayer, imported licensed car models, full open-world streaming, real-world vehicle simulation, or production-grade race AI. The six modes share the playable driving foundation, while race completion is currently a simple distance-based finish for non-free-roam modes.
