# 🌍 Planetary Annihilation Simulator 🚀💥

> An immersive 3D simulation where you launch nuclear warheads to destroy Earth. Built with **Three.js**,
> this project offers a darkly entertaining way to visualize global destruction in real-time. 🌐🔥

---

## 🎮 Features

- **3D Earth Simulation** using high-res textures and fallback rendering
- Realistic **Nuke Launcher** with selectable warhead types:
  - Tactical (1 MT)
  - Strategic (5 MT)
  - Tsar Bomba (50 MT)
- **Real-Time Destruction Meter** and global population tracker
- Smooth **camera orbit controls** using `OrbitControls`
- **Explosions & Fire Effects** rendered in 3D with visual feedback
- **Fallback Earth rendering** in case textures fail to load
- **Game Over** screen when destruction reaches 100%

---

## 🛠 Tech Stack

| Technology | Role |
|------------|------|
| [Three.js](https://threejs.org/) | Core 3D rendering |
| [Tailwind CSS](https://tailwindcss.com/) | Styling |
| HTML5 + Vanilla JS | Interface and logic |
| Fallback canvas texture | For offline rendering support |

---

## 🚀 How to Run Locally

1. **Clone the repository** or download the HTML file.
2. **Open `index.html`** directly in your browser.
3. **No server required!** Everything is client-side.

```bash
git clone https://github.com/yourname/planetary-annihilation-simulator.git
cd planetary-annihilation-simulator
start index.html
```
