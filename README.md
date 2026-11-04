<div align="center">
  <h1>🌀 Magnetic Particle Vortex Cursor</h1>
  <p><b>Interactive HTML5 Canvas galaxy swarm & click-shockwave physics in under 120 lines of pure Vanilla JS.</b></p>

  <p>
    <a href="https://nullxor.github.io/magnetic-vortex-cursor/">
      <img src="https://img.shields.io/badge/LIVE_DEMO-Play_in_Browser-00f5d4?style=for-the-badge&logo=googlechrome&logoColor=050508&labelColor=00f5d4" alt="Live Demo" />
    </a>
    <a href="https://www.instagram.com/nullxor/">
      <img src="https://img.shields.io/badge/Instagram-%40nullxor-07070c?style=for-the-badge&logo=instagram&logoColor=00f5d4&labelColor=07070c" alt="Instagram" />
    </a>
  </p>

  <p>
    <img src="https://img.shields.io/badge/HTML5_Canvas-E34F26?style=flat-square&logo=html5&logoColor=white" />
    <img src="https://img.shields.io/badge/Vanilla_JS-F7DF1E?style=flat-square&logo=javascript&logoColor=black" />
    <img src="https://img.shields.io/badge/Zero_Dependencies-9b5de5?style=flat-square" />
    <img src="https://img.shields.io/badge/60_FPS-00bbf9?style=flat-square" />
  </p>
</div>

---

### ⚡ What It Does

- **Magnetic Swarm Physics:** 800 individual neon particles dynamically calculate radial distance and tangential velocity to swirl into a glowing core around your cursor.
- **Click Shockwave Detonation:** Clicking anywhere triggers an outward radial impulse with an expanding alpha shockwave ring before sucking the stars right back in.
- **Zero External Libraries:** 100% self-contained in a single `index.html` file. No npm packages, no WebGL overhead, and smooth 60 FPS rendering.

---

### 🚀 Quick Start (Run in 10 Seconds)

1. Click on **[`index.html`](./index.html)** above and hit the **Copy raw file** button (or download the repo as a `.zip`).
2. Save it on your computer as `index.html`.
3. Double-click to open it in any browser—move your mouse to attract the swarm and click to detonate!

---

### 🎛️ Easy Customization Guide

Want to tweak the look for your own portfolio? Change these variables inside the `<script>` tag of `index.html`:

| Line | Variable | Default | What It Controls |
| :--- | :--- | :--- | :--- |
| **Line 36** | `colors` | Neon Cyan / Purple / Pink | Hex color palette of the stars |
| **Line 39** | `PARTICLE_COUNT` | `800` | Total number of stars (`400` = minimal, `1200` = dense galaxy) |
| **Line 70** | `this.pullSpeed` | `0.25` – `0.60` | How aggressively the stars chase your pointer |
| **Line 89** | `this.vx *= 0.92` | `0.92` | Friction/damping (`0.96` = looser orbits, `0.88` = tighter snap) |

---

<div align="center">
  <p>If you used this effect or learned something new, drop a <b>⭐ Star</b> on this repository!</p>
  <p>More daily interactive UI code, tech hacks & developer workflows on <a href="https://www.instagram.com/nullxor?dlrf=djc3MHlrOGd2ZTR5"><b>@nullxor</b></a></p>
</div>
