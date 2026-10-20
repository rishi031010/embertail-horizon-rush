# 🦊 Embertail: Horizon Rush

[![Play Live on GitHub Pages](https://img.shields.io/badge/🎮_Play_Live-Embertail:_Horizon_Rush-f97316?style=for-the-badge)](https://rishi031010.github.io/embertail-horizon-rush/)
[![Built with HTML5 Canvas](https://img.shields.io/badge/HTML5_Canvas-60FPS_Engine-0284c7?style=for-the-badge&logo=html5&logoColor=white)](https://github.com/rishi031010/embertail-horizon-rush)
[![Zero Dependencies](https://img.shields.io/badge/Web_Audio_API-Procedural_Synth-10b981?style=for-the-badge)](https://github.com/rishi031010/embertail-horizon-rush)

> **Sprint across a living, breathing desert horizon.**  
> **Embertail: Horizon Rush** is a high-octane 60FPS endless runner built from scratch using vanilla JavaScript, HTML5 Canvas, and real-time Web Audio synthesis. Guide an explorer fox across an evolving frontier that shifts seamlessly from blazing golden dusk to meteor-lit midnight and sun-drenched daybreak.

🚀 **[Play Embertail: Horizon Rush Live in Your Browser!](https://rishi031010.github.io/embertail-horizon-rush/)**

---

## ✨ What Makes It Special

- **🌅 Real-Time Day–Night Sky Engine (`120s` Dynamic Cycle):** Watch the world evolve through *Golden Dusk*, *Starry Night*, *Meteor Shower*, *Golden Sunbeams*, and *Clear Sky*. Nighttime activates the fox's warm explorer lantern aura, illuminated obstacle rims, and glowing chasm beacons so visibility stays crystal clear.
- **⚡ 70-Combo Spirit Fox Dash:** Chain **70 combos** through coins, energy pegs, and close-call dodges to supercharge your Spirit Meter. Unleash a **4-second invincible blue-flame sprint** that glides across bottomless chasms and shatters wooden crates for massive bonus points.
- **🏮 Firefly Companion & 2x Magnet Orb:** Snag rare Forest Lantern Orbs to summon an orbiting bioluminescent firefly companion for 10 seconds—activating wide-radius coin magnetism and a **2x Score Multiplier**.
- **🌠 Celestial Shooting Star Catches:** Time your leaps as shooting stars streak across the midnight sky to trigger a **`+500` Star Catch** combo surge.
- **🏆 10 High-Stakes Milestones & Synthesized Fanfare:** Conquer long-term challenges (*Centurion Flow 100x*, *Unstoppable Legend 200x*, *Grand Explorer 100k*, *Titan Breaker*, and more) rewarded with a custom 0.85s multi-voice brass/chime arpeggio fanfare.
- **🎨 Switchable Cosmetic Trails:** Cycle between *Glowing Embers*, *Sakura Petals*, *Northern Lights (Aurora)*, and *Desert Dust* in real time.
- **💾 Instant Persistence & Shareable Score Cards:** High scores, unlocked achievements, and equipped trails save automatically to `localStorage`, complete with a one-click **Copy Shareable Score Card** button on the Run Over screen.

---

## 🎮 Controls

| Action | Desktop (Keyboard / Mouse) | Mobile / Touch |
| :--- | :--- | :--- |
| **Jump** | `Space`, `Up Arrow`, `W`, or Left-Click | Tap anywhere on screen |
| **Long Slide / Duck (`0.75s`)** | `Down Arrow`, `S`, or click `SLIDE` button | Swipe down once or tap `SLIDE` button |
| **Spirit Fox Dash** | `Shift`, `E`, or click `SPIRIT` button | Tap `SPIRIT` button or Double-Tap screen |
| **Pause / Resume** | `P` or `Esc` | Tap `Pause` button in top-right HUD |

---

## 🛠️ Engineering Highlights

- **Custom 2D Skeletal & Physics Loop:** Articulated multi-limb running, jumping, and belly-sliding animations with velocity-based pitch rotation, squash-and-stretch landing physics, and mid-air jump buffering.
- **Procedural Pattern Generator:** Scales obstacle spacing and speed ramps (`PACE`) smoothly over time while aligning collectible arcs to the exact parabolic trajectory of the fox's jump.
- **Zero-Asset Web Audio Synthesizer:** Every jump whoosh, pitch-escalating coin chime, crate smash, and achievement fanfare is synthesized mathematically in real time using `AudioContext` oscillators.

---

## 💻 Run Locally

No build steps or external dependencies required. Clone the repository and open `index.html` in any browser:

```bash
git clone https://github.com/rishi031010/embertail-horizon-rush.git
cd embertail-horizon-rush
# Open index.html in your browser
```

---

## 👤 Author

**Rishi Raj** ([@rishi031010](https://github.com/rishi031010))