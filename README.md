# ⛏️ Block City: The Minecraft Mission

Guide **Maitha** to 🏫 School and **Jamilah** to 🏥 Hospital.  
Dodge germs, beat the class, and claim the **Hall of Fame**!

**▶️ Play:** https://school-hospital-game.web.app  
**🎞️ Quick trailer:** ![Gameplay trailer](docs/media/demo.gif)

---

## Features
- 🎮 Two characters, two destinations
- 🦠 Germs cost points (🟥 –10, 🟩 –5)
- 🏆 Live leaderboard (Firestore)
- 🎬 Short cinematic intro + welcome card
- 🔊 Chiptune music with Mute/Unmute
- 📱 Mobile-first, responsive UI

## How to Play
- **Move:** Arrow keys / onscreen controls  
- **Goal:** Maitha → School; Jamilah → Hospital  
- **Avoid:** germs  
- **Finish:** Both reach targets → score auto-saves

---

## Screenshots
<p align="center">
  <img src="docs/media/scene_welcome.png" width="560"><br>
  <em>Welcome Scene</em>
</p>
<p align="center">
  <img src="docs/media/mission_brief.png" width="560"><br>
  <em>Mission Brief</em>
</p>
<p align="center">
  <img src="docs/media/leaderboard.png" width="560"><br>
  <em>Class Leaderboard</em>
</p>
<p align="center">
  <img src="docs/media/hall_of_fame.png" width="420">
  <img src="docs/media/end_trophy.png" width="420"><br>
  <em>Hall of Fame & Victory</em>
</p>

---

## Run / Deploy
**Local:** open `index.html`  
*(or serve)*:
```bash
python3 -m http.server 8080
# or
npx http-server -p 8080
```

**Firebase Hosting (already set up)**

```bash
npm i -g firebase-tools
firebase login
firebase init hosting     # choose existing project
firebase deploy
```

---

## Tech

HTML/CSS/JS (vanilla) • Firebase Firestore & Hosting • Canvas 2D • Web Audio

---

### Credits

By **Maitha Alhammadi** — Data-Driven Storytelling Studio (UTS)