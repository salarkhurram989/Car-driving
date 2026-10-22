# Car-driving — Endless 3D

A browser-based 3D endless driving game built with Three.js.

## Run it
Open the GitHub Pages site after Pages is enabled for the repository, or serve this repository through any static web server. The game imports Three.js from jsDelivr, so an internet connection is required to load the 3D engine.

## Current gameplay
- 3D road, player car, traffic vehicles, roadside scenery, chase/hood/cockpit/cinematic cameras
- Endless Race, Free Drive, Time Trial, and Traffic Survival modes
- Easy, Medium, and Hard difficulty settings
- Adjustable traffic density (including 0%), traffic speed, behavior, vehicle mix, weather, graphics and units
- Garage with selectable cars, paint color, finish, wheel/spoiler/ride-height options
- Cash rewards, vehicle unlocks, engine/handling/brake upgrade levels, best-distance tracking and local save data
- Keyboard and touch controls; arrow-key defaults are prevented only while gameplay is active
- Responsive HUD for desktop and mobile

## Controls
- **W / Up Arrow:** accelerate
- **S / Down Arrow:** brake / reverse
- **A / Left Arrow:** steer left
- **D / Right Arrow:** steer right
- **Space:** handbrake (reserved for future tuning)
- **Shift:** boost
- **C:** switch camera
- **Escape:** pause/resume

## Save data
Progress is stored locally in the browser using `localStorage`. It does not sync between browsers or devices. Clearing site data will clear local progress.

## Notes
This is an initial playable browser implementation, not a full commercial console simulation. Advanced physical suspension, realistic audio, detailed cockpit interiors, animated rain, and full controller mapping remain future improvements. Please test the deployed build on desktop and mobile before treating it as release-ready.
