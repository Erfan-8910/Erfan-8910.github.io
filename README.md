# Milky Way 3D Portfolio

An interactive 3D personal website and portfolio built with **Three.js** and **WebGL GLSL Shaders**. This project showcases developer repositories, technical skills, and creative web experiments through an interplanetary journey across the Milky Way galaxy.

---

## What is this project?

Rather than a conventional text-based resume, this project provides a creative, immersive web experience that demonstrates frontend capabilities, WebGL rendering, and browser audio synthesis:

1. **Interactive Portfolio Presentation:** Visitors navigate through 3D space, stopping at realistic planetary waypoints to inspect recovered projects and developer telemetry.
2. **Creative Coding & Shaders:** Implements procedural GLSL shaders for celestial bodies, Rayleigh atmospheric scattering, dynamic cloud layers, specular water reflections, and a living galaxy particle system.
3. **Retro Terminal & Mini-Game:** A functional vintage CRT computer terminal with a command-line interface, theme customizer, and an arcade space mini-game.

---

## Core Components

- **Planetary Waypoints:**
  - **Earth (1.00 AU):** Specular ocean highlights, atmospheric Rayleigh scattering, and animated cloud veil.
  - **Mars (1.52 AU):** Iron-oxide terrain relief, Valles Marineris canyon, and CO2 polar ice caps.
  - **Saturn (9.58 AU):** Multi-layered gas band textures, Cassini-divided ice rings, and realistic globe shadows.
  - **Neptune (30.1 AU):** Deep azure methane absorption with high-altitude cirrus clouds and an orbiting communications relay.
  - **Kepler-8910 (Exoplanet):** Bioluminescent seas with dynamic, shimmering polar auroras.
  - **Ground Base (Observatory):** A vintage CRT computer resting on a dark ground surface under a black starry sky.

- **Living Galaxy Environment:**
  - Spiral Milky Way disk with galactic core bulge and absorption dust lanes.
  - Dynamic shooting stars and meteors with burning ion trails.
  - Elastic 50-degree viewport look-around with smooth spring-back damping.

- **Ambient Audio:**
  - Peaceful polyphonic chord progressions and celestial bells synthesized natively via the Web Audio API without external audio files.

---

## Navigation & Controls

| Input | Action |
| :--- | :--- |
| **Scroll / Swipe** | Cruise between planetary waypoints |
| **Click & Drag** | Tilt viewport angle (up to 50°, springs back on release) |
| **Arrow Keys `↑` / `↓`** | Previous / Next waypoint |
| **Keys `1` to `6`** | Direct navigation to specific waypoint |
| **Key `T`** | Open interactive CRT terminal |
| **Key `P`** | Open projects & skills modal |
| **Key `M`** | Toggle ambient soundtrack |
| **Key `L`** | Switch language (English / Persian) |

---

## Tech Stack

- **3D Graphics & Shaders:** Three.js (WebGL 2.0 / GLSL)
- **Audio Engine:** Web Audio API (Native browser synthesis)
- **UI & Layout:** HTML5, Modern CSS3, JavaScript (ES6+ Modules)
- **Data Integration:** GitHub REST API v3
- **Hosting:** GitHub Pages

---

## License

This project is open source and available under the [MIT License](LICENSE).
