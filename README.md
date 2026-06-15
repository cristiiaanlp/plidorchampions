# ⚽ Plidor Champions

A single-file arcade soccer game — pure HTML, CSS and Canvas JavaScript, **no external dependencies**. Built to run smoothly on desktop and mobile, ready for portals like Poki and CrazyGames.

## ▶ Play

Just open `index.html` in any modern browser (or serve the folder with a tiny local server such as `python -m http.server`).

## ✨ Features

- **Game modes:** Quick Match, World Cup Chaos (random madness every few seconds), Tournament (8-team bracket), Daily Challenge (seeded), and local 2-Player.
- **Physics-driven arcade gameplay:** big-head characters, satisfying ball bounces, power-ups, spectacular goals.
- **Power-ups:** Fire Shot, Freeze, Giant Head, Speed Boost, Mega Jump, Magnet Ball — plus chaos events (giant goals, low gravity, tornado, multi-ball, and more).
- **Progression:** coins, 8 character skins, 6 ball skins, achievements/missions, local leaderboard.
- **Living Arenas** — 5 interactive stadiums, each with a permanent physics rule (ice rink, low gravity, sea breeze) and props you and the ball bounce off (pinball bumpers, trampolines, erupting lava geysers). No two pitches play the same.
- **Polish:** camera shake, particles, confetti, fireworks, synthesized audio, screen flash, haptics.
- **Save:** progress, stats and settings persist in `localStorage`.
- **Platform-ready:** loading screen, ad hooks (CrazyGames / Poki SDK with local stub), rewarded/interstitial flow.

## 🎨 Art assets (optional)

The game draws everything procedurally by default. Drop PNGs into `assets/` to replace any element — missing files automatically fall back to procedural art, so the game never breaks. See in-code comments and folder structure (`assets/stadiums`, `assets/skins`, `assets/balls`, `assets/powerups`).

## 🛠 Controls

- **Player 1:** `A` / `D` move · `W` jump · `Space` kick
- **Player 2:** `←` / `→` move · `↑` jump · `Enter` kick
- **Mobile:** on-screen buttons

## 📦 Tech

Single `index.html`, Canvas rendering at a fixed logical resolution scaled responsively, 60 FPS target, WebAudio-synthesized sound. No frameworks, no build step.
