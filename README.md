<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:20242b,100:eccc74&height=200&section=header&text=A.i.Atik&fontSize=70&fontColor=ffe8a8&animation=fadeIn&fontAlignY=38&desc=Sand%20Text%20Animation&descAlignY=58&descSize=20" width="100%"/>

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=22&duration=3000&pause=800&color=ECCC74&center=true&vCenter=true&width=560&lines=Text+built+from+thousands+of+falling+grains...;Sand+piles%2C+settles%2C+and+erodes+naturally...;A+hidden+message+fades+in...;Then+rises+back+into+shape.+Forever+looping." alt="Typing SVG" />

<br/>

![Status](https://img.shields.io/badge/status-active-brightgreen?style=for-the-badge)
![Made with JS](https://img.shields.io/badge/JavaScript-ES6+-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Canvas](https://img.shields.io/badge/HTML5-Canvas-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![License](https://img.shields.io/badge/license-MIT-blue?style=for-the-badge)

</div>

---

## 🌊 What It Does

This is a **zero-dependency, physics-driven particle animation** that spells out text using thousands of individually simulated sand grains. Watch the loop:

```
 ┌─────────────┐     ┌──────────┐     ┌───────┐     ┌───────────┐     ┌────────┐
 │  Text forms │ ──▶ │ Erodes & │ ──▶ │ Falls │ ──▶ │  Settles   │ ──▶ │ Reveals │
 │  from sand  │     │ releases │     │ down  │     │ into pile  │     │ message │
 └─────────────┘     └──────────┘     └───────┘     └───────────┘     └────┬────┘
        ▲                                                                   │
        └───────────────────────  Reforms back into text  ◀─────────────────┘
```

| Phase | What happens |
|:---:|---|
| 🔤 **Text Formation** | Particles assemble into **"A.i.Atik"** |
| 💨 **Release** | Edge grains break free first — natural erosion |
| 🌧️ **Falling** | Gravity + wind drift simulate real motion |
| ⛰️ **Piling** | Grains stack and settle like a real sand pile |
| ✨ **Reveal** | A hidden message fades in |
| 🔁 **Reform** | Sand rises back into the text, and the loop repeats |

---

## 🛠️ Tech Stack

<div align="center">

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Canvas API](https://img.shields.io/badge/Canvas_API-000000?style=flat-square&logo=html5&logoColor=white)

</div>

- **HTML5 Canvas** — pixel-level particle rendering, no libraries
- **Vanilla JavaScript (ES6+)** — custom physics loop (gravity, drag, drift, settling)
- **CSS3** — full-viewport responsive layout

## 📁 Project Structure

```
A.i.Atik-Sand-Animation/
├── index.html      # Entry point
├── script.js       # Particle physics & animation engine
├── style.css        # Styling
└── README.md        # You are here
```

## 🚀 Getting Started

```bash
git clone <your-repo-url>
cd A.i.Atik-Sand-Animation
open index.html      # or just double-click it — zero build step
```

**Optional local server:**
```bash
npx serve .
```

## ⚙️ Configuration

Every knob lives in the `settings` object at the top of `script.js` — tweak and reload:

```js
const settings = {
  cellSize: 3,                 // grain size in px
  startText: "A.i.Atik",       // text formed by sand
  hiddenText: "...",           // message revealed mid-cycle
  gravity: 850,                // fall acceleration
  airDrag: 0.992,               // air resistance
  pileHoldSeconds: 0.8,        // pause before reveal
  reformDurationSeconds: 2,    // time to reform into text
  revealHoldSeconds: 3         // how long the message stays
};
```

| Setting | Effect |
|---|---|
| `cellSize` | Grain resolution — smaller = finer detail, more particles |
| `gravity` / `airDrag` | Controls fall speed & floatiness |
| `releaseChance` | How eagerly the text erodes |
| `reformStaggerSeconds` | Spread of arrival times during reform |

## 📱 Responsive by Design

The canvas rebuilds its entire particle grid on resize — text scale, grain density, and physics all adapt live to any screen size.

---

<div align="center">

### 👨‍💻 Developer

**MD. Atiqul Islam (Atik)**

[![Email](https://img.shields.io/badge/Email-atikcmttiu1001%40gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:atikcmttiu1001@gmail.com)

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:eccc74,100:20242b&height=100&section=footer" width="100%"/>

**Licensed under MIT** — free to use, remix, and build on.

</div>
