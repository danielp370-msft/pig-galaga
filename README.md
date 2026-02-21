# 🐷 Pig Galaga

**Three arcade games where you battle an angry pig family in space.** Built entirely through conversational prompting with GitHub Copilot — no manual coding, no build tools, no frameworks beyond Three.js.

## 🎮 Play Now

<a href="https://danielp370-msft.github.io/pig-galaga/">
  <img src="https://img.shields.io/badge/%F0%9F%90%B7%20PLAY%20NOW-Pig%20Galaga-ff69b4?style=for-the-badge&logoColor=white" alt="Play Pig Galaga" />
</a>

### 🎬 Demo

<!-- TO ADD YOUR VIDEO: Edit this README on GitHub, delete this comment and the placeholder text below, then drag-drop your .mp4 file here. GitHub will auto-upload it and generate the video embed. -->
*Video coming soon — drag-drop your MP4 here when editing on GitHub!*

## 🐖 Meet the Pig Family

- **Baby Pig** — Pink and fast, basic foot soldier
- **Mama Pig** — Wears a bow, slightly tougher
- **Papa Pig** — Top hat, takes more hits
- **Grandpa Pig** — Gold glasses, crafty old-timer
- **🥓 The Bacon King** — Golden crown, glowing aura, boss of bosses

## 🛠️ How This Was Made

This entire project was built through natural language conversation with **GitHub Copilot** in the terminal. No code was written by hand. The process went something like:

> *"Make me a web version of Galaga with cartoon pigs as the villains"*

...and then dozens of iterative prompts like:

- *"Add pig oink sound effects"*
- *"Make a 3D version with Three.js"*
- *"Now make a full 3D space shooter where I fly around"*
- *"The pigs should swarm around me in V-formations"*
- *"Add a radar minimap"*
- *"Make a landing page with 3D pigs bouncing in the background"*

Each game is a **single HTML file** — no bundlers, no npm, no build step. Just open the file in a browser and play. Three.js is loaded from a CDN. All sound effects are synthesized with the Web Audio API (oinks, laser pews, explosions — no audio files needed).

The whole thing was genuinely fun to build. Copilot handled everything from the initial game loop to fine-tuning pig AI behavior, collision physics, touch controls, and deployment to GitHub Pages. It felt more like directing a game than programming one.

## 🔗 Direct Game Links

Don't want the landing page? Jump straight into a game:

| Game | Link | Description |
|------|------|-------------|
| 👾 **Classic 2D** | [Play](https://danielp370-msft.github.io/pig-galaga/galaga-2d.html) | Old-school Galaga with pig formations dive-bombing from above |
| 🎮 **3D Battle** | [Play](https://danielp370-msft.github.io/pig-galaga/index3d.html) | Same arcade gameplay with Three.js lighting, shadows & particles |
| 🚀 **Space Shooter** | [Play](https://danielp370-msft.github.io/pig-galaga/index-space.html) | Full 3D dogfighting — pig squads in V-formation swarm around you |

## 🕹️ Controls

### Classic 2D / 3D Battle
- **Arrow keys** or **A/D** — Move left/right
- **Space** — Shoot
- **Touch** — Tap sides to move, tap center to shoot

### Space Shooter
- **Mouse** — Aim and steer
- **Click** — Shoot
- **Right-click** — Bomb (limited supply)
- **Touch** — Single finger to aim, double-tap for bombs

## 📁 Project Structure

```
index.html        — Landing page (game picker with 3D pig background)
galaga-2d.html    — Classic 2D Galaga
index3d.html      — 3D Battle (Three.js)
index-space.html  — Full 3D Space Shooter
```

Each file is completely self-contained. No dependencies to install. No server required (though you'll need one for local testing due to ES module imports).

## 🚀 Run Locally

```bash
# Any simple HTTP server works
python3 -m http.server 8080
# Then open http://localhost:8080
```

## License

MIT — do whatever you want with it. Oink oink. 🐷
