# Car-driving — Endless 3D

A browser-based 3D endless driving game built with Three.js and WebGL. The game source is in `index.html`; no build step is required.

## Run the game
- Open the repository's GitHub Pages site if Pages is enabled, or serve the repository using any static web server.
- An internet connection is required to load Three.js from jsDelivr.
- Use a modern browser with WebGL support. Audio starts after driving begins because browsers require user interaction before playing audio.

## Game modes
- **Endless Race** — endless driving, score and cash rewards.
- **Free Drive** — no forced timer or finish; traffic can be set to 0%.
- **Time Trial** — timed 90-second challenge.
- **Traffic Survival** — survive traffic and collision damage.
- **Checkpoint Challenge** — drive to the 3 km target.
- **Custom Race** — configurable traffic and difficulty session.

## Features
- Procedural 3D player car, traffic cars, continuous road segments, roadside trees/buildings, shadows and multiple camera views.
- Chase, hood, cockpit and cinematic camera options.
- Clear day, sunset, night, rain particle effect and fog presets; night headlights.
- Easy, Medium and Hard difficulty affects traffic speed and rewards.
- Adjustable traffic density, speed, aggression, vehicle type, maximum vehicles and spawn distance.
- Garage with selectable vehicles, paint color, gloss/matte/metallic finish, wheel style, spoiler and ride height.
- Engine, handling and brake upgrades that affect driving stats.
- Cash, vehicle purchases, mission rewards, score, distance records and player level.
- Collision damage can be enabled or disabled; Free Drive continues after collisions.
- Keyboard, pointer/touch controls and basic gamepad support.
- Procedural engine sound and collision feedback.
- Browser-local saving for settings, cash, vehicles, upgrades, customizations and statistics.

## Controls
- **W / Up Arrow:** accelerate
- **S / Down Arrow:** brake / reverse
- **A / Left Arrow:** steer left
- **D / Right Arrow:** steer right
- **Space:** handbrake
- **Shift:** boost
- **C:** change camera
- **Escape:** pause/resume
- **Gamepad:** left stick steers; triggers accelerate/brake; A/first button activates boost.

## Saving
Progress is stored in the current browser using `localStorage`. It does not sync between browsers or devices. Clearing site data removes local progress. The Settings screen includes manual save and a confirmed reset-progress action.

## Current limitations
This is an expanded playable browser-game foundation, not yet a full commercial console simulation. The cars are procedural models rather than licensed high-detail vehicle assets; physics are lightweight arcade-style rather than a full rigid-body/tire simulation; the cockpit is not a detailed interior; and not every requested body-kit part, controller remapping option, audio channel, or environment biome is implemented yet. Please test the live deployment on desktop and mobile before treating it as release-ready.
