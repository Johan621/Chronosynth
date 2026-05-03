# Chronosynth

A real-time HTML5 Canvas game built with pure Vanilla JavaScript.  
No libraries. No assets. No frameworks.

Uses time as a weapon. Deploy **Echos** of your past movement to manipulate AI, herd energy cores, and outsmart predictive hunters.

---

## 🎮 Play Online (GitHub Pages)

**Live Demo**  
https://johan621.github.io/Chronosynth/


---

## 🧠 Gameplay Mechanics

- **Echo System** — replay your last 3 seconds infinitely
- **Adaptive Core AI** — cores flee from you, follow your Echos
- **Phase Shift every 15 seconds**
  - **GATHER**: push cores into the Nexus
  - **HUNT**: touch cores directly (Nexus repels)
- **Predictive Hunters** — enemies aim where you *will* be

---

## 🕹 Controls

| Action | Input |
|-------|-------|
| Move | Mouse / Touch |
| Deploy Echo | Spacebar / Echo button |

---

## ✨ Features

- High FPS Canvas rendering
- Procedural particles, glow, and trails
- Sound effects using Web Audio API
- Screen shake and visual feedback
- Mobile compatible
- Zero dependencies
- Clean ES6 class architecture

---

## 🛠 Tech Used

- HTML5
- CSS3
- JavaScript (ES6)
- Canvas API
- Web Audio API

---

## ▶️ Run Locally

Open `index.html` in any modern browser.

---

## 🌍 Host on GitHub Pages (Steps)

1. Create a new repository named **chronosynth**
2. Upload `index.html` to the root
3. Go to **Settings → Pages**
4. Source:
   - Branch: `main`
   - Folder: `/ (root)`
5. Save and wait ~30 seconds

Your game will be live at:  
`https://your-username.github.io/chronosynth/`


---

## 🏗 Architecture

| Class | Responsibility |
|------|-----------------|
| GameManager | Main loop, state, collisions |
| Player | Movement and history tracking |
| Echo | Replays past movement |
| Core | AI behavior and phase logic |
| Hunter | Predictive AI enemy |
| Nexus | Phase interaction zone |
| Particle | Visual effects |
| AudioEngine | Procedural sound effects |
| MathUtils | Vector helpers |

---

## 🏁 Objective

**Win:** Collect 30 cores (100% Resonance)  
**Lose:** Hit by hunters 3 times

---

