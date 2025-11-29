# Space Dino v4.2

A physics-based space grappling game featuring a cyber-dinosaur and co-pilot navigating through increasingly dangerous cosmic environments.

## Game Overview

Control a purple cyber-dino with a curly-haired co-pilot as you swing through space using a grappling hook mechanic. Avoid asteroids, comets, shooting stars, and black holes while traveling as far as possible through four distinct zones. Protect your co-pilot - lose them and you'll need to survive 300m for automatic rescue!

## How to Play

- **Tap/Click & Hold**: Grapple to the nearest anchor point
- **Double Tap/Click**: Dash forward (cooldown applies)
- **Release**: Let go of the rope and swing freely

## Co-Pilot System

Your cyber-dino carries a co-pilot who acts as a shield:
- **First hit**: Co-pilot is ejected, you gain temporary invulnerability (2 seconds)
- **Auto-rescue**: Survive 300m without your co-pilot and they automatically return to restore your shield
- **Second hit** (without co-pilot): Game over

## Zones & Hazards

1. **Atmosphere** (0-1000m): Safe zone with basic anchors
2. **Asteroid Belt** (1000-2000m): Rotating space debris appears
3. **Meteor Shower** (2000-5000m): Fast-moving shooting stars with velocity trails
4. **Event Horizon** (5000m+): Black holes with gravitational pull and spaghettification risk

### Hazard Types

- **Asteroids**: Rotating debris (spawns from 1000m+)
- **Comets**: Slow-moving projectiles with trails (spawns from 1000m+)
- **Shooting Stars**: Fast white streaks (spawns from 2000m+)
- **Black Holes**: Gravitational wells that pull you in; direct contact = spaghettification (spawns from 5000m+)

## Features

- **Two-hit system** with co-pilot shield and auto-rescue feature
- **Realistic rope physics** and momentum-based movement
- **Black hole gravity wells** with slingshot mechanics and spaghettification
- **Progressive difficulty** with four distinct zones
- **Multiple hazard types** including asteroids, comets, shooting stars, and black holes
- **Visual feedback** including zone warnings, alerts, and speed display
- **Procedural level generation** with dynamic hazard spawning
- **Local high score** tracking
- **Retro sci-fi aesthetic** with custom Web Audio API sound effects
- **Fully responsive** (desktop & mobile with touch support)

## Running the Game

Simply open `index.html` in any modern web browser. No build process or dependencies required.

## Technologies

- Vanilla JavaScript (ES6+)
- HTML5 Canvas for rendering
- Tailwind CSS (via CDN) for UI
- Web Audio API for procedural sound generation
- Orbitron Google Font for cyberpunk aesthetic

## Tips

- **Protect your co-pilot**: Avoid hazards when possible - losing them makes the game much harder
- **Time your releases**: Let go of the rope at the right angle for maximum forward momentum
- **Use the dash wisely**: The 2-second cooldown means you should save it for emergencies
- **Black hole strategy**: Gravity wells can slingshot you forward if you approach from the side
- **Auto-rescue mechanic**: After losing your co-pilot, survive 300m to automatically get them back and restore your shield
- **Invulnerability window**: After losing your co-pilot, you have 2 seconds to escape danger
