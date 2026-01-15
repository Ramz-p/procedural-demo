# Procedural Demo 🟢🎮

> From a 4KB corridor… to a playable procedural FPS.

This repository started as a **4KB procedural corridor experiment** inspired by the legendary **.kkrieger** philosophy:
> *Generate everything. Ship nothing.*

It has now evolved into a **fully playable procedural FPS prototype** — still asset-free, still experimental, and still obsessed with doing more using less.

Welcome to **procedural-demo**.

---

## 🎮 What This Is

A **procedural game experiment** built entirely in:
- HTML
- JavaScript
- Three.js
- Math (lots of it)

No imported assets.  
No textures.  
No sound files.  
No engines.  

Everything you see *and hear* is generated at runtime.

---

## 🕹️ How to Play

1. Download `game.html`, `game2.html`, or `game3.html` (your choice)
2. Open it in a modern browser (Chrome / Firefox / Edge)
3. Click to lock the mouse and start playing

### Controls
- **WASD** — Move  
- **Mouse** — Look around  
- **Click** — Shoot  

If your browser asks for permission → say **yes**, it’s worth it 😄

---

## 🧠 Project Phases

### 🟩 Phase 1 — 4KB Procedural Corridor
- Infinite corridor
- Procedural textures
- Automatic forward motion
- Head-bob + lighting atmosphere
- Inspired directly by size-restricted demos like `.kkrieger`

This phase proved:
> “Yes, you can generate entire worlds in a few kilobytes.”

---

### 🟢 Phase 2 — Playable FPS Prototype
- First-person shooter controls
- Pointer-lock mouse look
- Shooting & hit detection
- Enemies with health, movement, and death
- Player health & score system
- Procedural arena generation

---

### 🟥 Phase 3 — The Maze & The Shotgun (New!)
**File:** `game3.html`

Phase 3 introduces actual level structure and weapon variance.

#### New Features
- **Maze Generation (Recursive Backtracker):** Instead of an open arena, the world is now a claustrophobic 15x15 maze generated at runtime. No two runs are the same.
  
- **Shotgun Mechanics:** Replaced the single-shot laser with a procedural shotgun. It fires 5 raycast spreads per click with randomized recoil.
  
- **Physics & Collision:** Added player-to-wall collision detection (wall sliding) so you can navigate the maze without clipping through geometry.

- **Audio Upgrade:** New procedural sound synthesis for the shotgun blast (Sawtooth + Square waves) to give it a "heavier" punch compared to Phase 2.

- **Atmosphere:** Added heavy distance fog to obscure enemies until they are close.

---

## 📸 Screenshot / Visual

phase 1 <img width="1438" height="686" alt="Procedural FPS Screenshot" src="https://github.com/user-attachments/assets/3b310309-37d5-41d7-8c83-55226f54f5ef" />
phase 2 <img width="1440" height="686" alt="Screenshot 2026-01-14 at 02 32 42" src="https://github.com/user-attachments/assets/555ad62d-e8f6-494e-ad38-8d419259f14f" />
phase 3 <img width="1437" height="688" alt="Screenshot 2026-01-16 at 01 16 09" src="https://github.com/user-attachments/assets/bc2e7979-2f1b-4e4b-bf56-fee1659e22e8" />



*(Yes, this is all generated. No, there are no assets.)*

---

## 🧩 Tech Stack

- [Three.js](https://threejs.org/) — WebGL rendering
- Canvas API — Procedural textures
- Web Audio API — Procedural sound
- Pure HTML + JS — No build tools, no frameworks

---

## 😎 Developer Notes

- This is **not a AAA game** — it’s a AAA *idea* squeezed into a tiny box.
- If this feels like an old demo scene project… good. That’s intentional.
- Infinite procedural systems = infinite bugs = infinite fun.
- If someone asks “what genre is this?”, the correct answer is:
  **“Yes.”**

---

## 🚧 What’s Next

- Smarter enemy behaviors
- More aggressive procedural arenas
- Better pacing & difficulty curves
- Further pushing the “systems over assets” philosophy

This is not a finished game.  
It’s a **living experiment**.

---

## 📜 License

MIT License — use it, remix it, break it, just give credit.

---

Made with 💚 and controlled chaos by  
**[@NormieGames](https://github.com/Ramz-p)** ```
