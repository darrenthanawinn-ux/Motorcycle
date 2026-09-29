# 🏍️ Apex Drift: Neon Highway

> An advanced, production-grade single-file motorcycle racing simulator built with Three.js, Tailwind CSS, and Web Audio API. Featuring authentic two-wheeler leaning physics, dynamic particle effects, a dual-channel procedural sound synthesizer, and a cyberpunk neon aesthetic.

![Apex Drift Preview](https://img.shields.io/badge/status-active-success.svg)
![Technologies](https://img.shields.io/badge/tech-Three.js_%7C_Tailwind_%7C_Web_Audio-blueviolet)

---

## ✨ Key Features

* **True Motorcycle Physics:** Simulates real two-wheeler leaning mechanics, counter-steering, and rider body-weight shifts tied directly to your cornering velocity and turn rate.
* **Procedural Web Audio Engine:** Custom synthesizer that generates dynamic engine RPM drones (scaling with throttle and velocity) and tire friction hiss during high-speed drifts.
* **Dual Camera System:** Instantly toggle between a smooth tracking **Chase Cam** and an immersive **Driver/Helmet View** (`C` key).
* **Cyberpunk Neon Atmosphere:** Fully configurable time-of-day presets (*Cyber Sunset*, *Deep Night*, *Overcast Day*), instanced neon streetlamps, exponential fog, and dynamic shadows.
* **Interactive HUD & Minimap:** Live speed readout (km/h / mph support), real-time lean angle indicator, and a rotating minimap tracking your position across the circuit.

---

## 🎮 Controls

| Key / Control | Action |
| :--- | :--- |
| <kbd>W</kbd> or <kbd>S</kbd> / <kbd>↑</kbd> <kbd>↓</kbd> | Throttle / Brake & Reverse |
| <kbd>A</kbd> or <kbd>D</kbd> / <kbd>←</kbd> <kbd>→</kbd> | Counter-steer / Lean into turns |
| <kbd>Space</kbd> | Rear brake / Drift slide |
| <kbd>C</kbd> | Switch Camera View (Chase ↔ Driver Cam) |
| <kbd>H</kbd> | Toggle Headlights |
| <kbd>Esc</kbd> | Open Simulation Settings |

---

## 🚀 Getting Started

Because `Apex Drift` is packaged as a **single-file application**, running it takes seconds:

1. Copy the game code and save it as `moto_simulator.html` in your project folder.
2. Open `moto_simulator.html` directly in any modern browser (Chrome, Firefox, Edge, Safari).
3. Click **"Ignite Engine"** and hit the neon highway!

---

## 🛠️ Tech Stack

* **[Three.js (r128)](https://threejs.org/):** 3D graphics rendering, custom instanced meshes, and camera tracking.
* **[Tailwind CSS](https://tailwindcss.com/):** Modern glassmorphism UI styling.
* **Web Audio API:** Real-time oscillator synthesis for engine and tire sound effects without external audio asset dependencies.

---

## 📝 License

Distributed under the MIT License. Feel free to fork, modify, and build upon it!