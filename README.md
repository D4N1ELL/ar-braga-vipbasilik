# 🌟 The Four Stickers of the Campus Quest — AR Experience

An immersive AR (Augmented Reality) web application that blends storytelling, sequential NFT marker detection, and 3D objects into a cohesive interactive experience.
This project showcases AR.js capabilities using **multi-stage marker progression**, **floating hint panels**, and a **unified coder-themed storyline** set in a Technical University environment.

---

# 🎯 Project Features

### 📊 Grade Requirements Implementation

| Grade    | Implementation                                                                               |
| -------- | -------------------------------------------------------------------------------------------- |
| **5** ✅  | Displays one object when scanning a single sticker                                           |
| **7** ✅  | Sequential unlocking: each sticker appears *only after the previous one is scanned*          |
| **9** ✅  | Multi-step scenario with narrative progression and dynamic hint panels                       |
| **10** ✅ | Rich artistic/narrative value inspired by student life, coding culture, and machine learning |

---

# 🎮 Experience Overview

**The Four Stickers of the Campus Quest** takes users through four symbolic AR markers representing a coder's journey:

1. **Specialty Logo** — The beginning
2. **Coffee Cup** — The fuel
3. **Coding Joke** — The spirit
4. **Sigmoid Curve** — The transformation

Each sticker reveals:

* A unique 3D object
* A floating hint panel
* A narrative clue guiding the player to the next marker

This experience is **progressive**, requiring players to follow the storyline step-by-step.

---

# 🏫 Sticker 1 — Specialty Logo

### **Stage: Initialization**

**Displayed Content**

* A floating holographic 3D emblem of the faculty
* A translucent floating hint panel

**Hint Panel Text**

> *"A good program starts with a declaration.
> Your journey begins where students get their fuel.
> Find the place powered by caffeine."*

🔓 Unlocks Sticker 2 (Coffee Cup)

---

# ☕ Sticker 2 — Coffee Cup

### **Stage: Compiler's Brew**

**Displayed Content**

* A steaming 3D coffee cup hovering above the marker
* A floating hint panel

**Hint Panel Text**

> *"Even code needs energy to run.
> But humor keeps developers sane.
> Look for the sticker that makes you laugh."*

🔓 Unlocks Sticker 3 (Coding Joke)

---

# 😂 Sticker 3 — Coding Joke

### **Stage: Debugging the Mood**

**Displayed Content**

* A floating text panel with a coding joke
* An ASCII-style floating emoji
* A subtle animation for engagement

**Hint Panel Text**

> *"A smile fixes many bugs.
> For your final clue, follow the curve
> that turns noise into signal… smoothly."*

🔓 Unlocks Sticker 4 (Sigmoid Curve)

---

# 📈 Sticker 4 — Sigmoid Curve

### **Stage: Activation Complete**

**Displayed Content**

* A glowing animated sigmoid curve
* A hint panel suspended above it
* Smooth animated transition from low → high value

**Final Message**

> *"From initialization to activation,
> you have followed the coder's path.
> Congratulations, you completed the Architect's quest."*

🎁 After the hint fades, a **3D Developer's Key** briefly appears as the final reward.

---

# 🔧 Technical Implementation

### Core Technologies

* **A-Frame** — 3D/VR framework for web
* **AR.js** — NFT marker-based AR tracking
* **JavaScript** — State management & sequential logic
* **GLTF/GLB** — 3D models for AR objects
* **HTML/CSS** — Interface and responsive layout

### Key Features

* **Sequential Marker Detection**
  Stickers appear in required order; next stages unlock only when previous markers are scanned.

* **Progress Tracking**
  JavaScript state arrays track:

  * discovered markers
  * unlocked stages
  * displayed hints

* **Floating Hint Panels**
  Clean UI above objects using `<a-entity>` + text geometry.

* **Mobile Compatibility**
  Works on Android/iOS web browsers with camera support.

---

# 🎨 Artistic Elements

### Visual Design

* Consistent coder aesthetic across all markers
* Floating holographic hints
* Animated sigmoid curve for a polished finale
* Subtle glowing effects on 3D objects

### Narrative Structure

* **Beginning:** Declaration of the quest
* **Middle:** Humor and energy of student life
* **End:** Machine learning symbolism and mastery

The entire story mirrors the phases of learning programming.

---

# 📁 File Structure

```
campus-quest-ar/
├── index.html                     # Main AR application
├── README.md                      # Documentation
├── images/                        # NFT marker files
│   ├── specialty.*                # Marker 1
│   ├── cofy.*                     # Marker 2
│   ├── joke.*                     # Marker 3
│   └── sigmoid.*                  # Marker 4
├── assets/
│   ├── specialty_logo.glb         # 3D emblem model
│   ├── coffee_cup.glb             # 3D cup model
│   ├── joke_panel.png             # Joke texture
│   ├── sigmoid_curve.glb          # Animated sigmoid
│   └── developers_key.glb         # Final reward
├── style.css                      # UI styling
├── logic.js                       # State management logic
└── textures/                      # Additional textures
```

---

# 🚀 Getting Started

### Prerequisites

* Smartphone or laptop with camera
* HTTPS connection
* Printed NFT markers (or displayed on another screen)

### Running the Experience

1. Generate marker files using NFT Marker Creator
2. Host project via GitHub Pages / Render / Netlify
3. Open the AR webpage
4. Allow camera access
5. Scan the **Specialty Logo** first
6. Follow floating hints to progress

---

# 🎯 Interactive Features

* **Progressive Unlocking** — Each sticker requires the previous one
* **Dynamic UI** — Hint panels adjust per stage
* **Thematic Storytelling** — Each object advances the narrative
* **Animated Finale** — Moving sigmoid + Developer's Key reward

---

# 🏆 Achievement System

* 🥉 *Beginner Coder:* Scan the first sticker
* 🥈 *Caffeine Addict:* Reach the second sticker
* 🥇 *Debugger Hero:* Discover the joke sticker
* 💎 *Architect of Activation:* Complete the full 4-step quest

---

# 📝 Development Notes

### Marker Detection

* NFT-based recognition for reliable scanning
* Smoothing tuned for stability
* Sequential logic blocks skipping ahead

### Performance Optimizations

* Light 3D models
* Efficient animations
* Caching of preloaded assets

---


