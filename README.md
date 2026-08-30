# Minecraft — 3D Grid Engine

A browser-based Minecraft-style voxel engine prototype.

## Current build

- Real-time 3D first-person world using Three.js
- Grid/voxel world with monochrome blocks rather than coloured textures
- Procedural starter terrain
- WASD movement
- Mouse look with pointer lock
- Jumping and basic collision
- Sprint with Shift
- Break blocks with left click
- Place blocks with right click
- 9-slot hotbar and number-key selection
- Inventory screen with E
- Pause menu with Escape
- Settings for FOV, mouse sensitivity and render distance controls
- Day/night light movement
- Crosshair and coordinates HUD
- Local browser world saving
- Reset-world button
- Responsive UI

## Run

Open `index.html` in a modern browser. The engine imports Three.js from jsDelivr, so an internet connection is required.

This is an original Minecraft-style engine prototype and does not include Mojang assets or textures.

## Roadmap

The architecture is intentionally small so more Minecraft systems can be added next: chunk streaming, block types, proper inventory stacks, crafting, entities/mobs, health/damage, tools, particles, audio, multiplayer and a more complete settings system.
