# Aimulator+

A browser-based mouse sensitivity simulator for FPS games. Feel your real sensitivity before you queue up, and warm up your aim without launching the game.

Enter your real DPI and in-game sensitivity, and Aimulator+ reproduces your true aim feel with accurate DPI/eDPI/cm-360 calculations. Originally built for tactical shooters (Valorant, CS2, Apex Legends, Overwatch 2, Rainbow Six Siege), it includes a built-in aim-training minigame with reaction-time tracking.

## Why Aimulator+?

Warming up your aim or comparing sensitivities across games usually means launching each title, navigating menus, and adjusting settings just to feel the difference. Aimulator+ reproduces your exact sensitivity using per-game yaw values — so you can dial in your sens and train your muscle memory in seconds, right in the browser.

## Features

- **True Sensitivity Simulation** — Converts real DPI + sens into authentic movement using per-game yaw constants (degrees per count).
- **Game Profiles** — Valorant, Counter-Strike 2, Apex Legends, Overwatch 2, Rainbow Six Siege, plus a neutral Default profile.
- **Live Stats** — Real DPI, Sim DPI, eDPI, and cm/360 calculated in real time.
- **eDPI Lock** — Swap DPI presets while keeping your effective sensitivity constant.
- **Crosshair Styles** — Valorant Classic, CS2, Apex Dot, and Overwatch styles.
- **Aim Minigame** — 20-second reflex run with countdown, live timer, and per-target reaction log (fastest/slowest/average), with escalating music tempo and a confetti finish.
- **Local Leaderboard** — Top 5 runs saved in your browser.
- **Challenge Links** — Share your score as a link; friends see your challenge banner when they open it.
- **Fold-Away HUD** — Clean canvas during runs, with tab-peek panels when idle.

## Privacy & Architecture

Aimulator+ is designed with a **local-first** philosophy. Here is exactly what that means for your data:

- **Runs Entirely Client-Side:** Everything happens in your browser. There is no server, no backend, and no account system.
- **Zero Telemetry:** No tracking, no analytics, no update checks. The application does not "phone home."
- **Local Storage Only:** Leaderboard entries and settings are saved in your browser's local storage and never leave your machine.
- **No External Requests:** Aside from Google Fonts, the app makes no network requests at runtime.

> **In short:** Nothing you do in Aimulator+ ever leaves your computer.

## Live Demo

Play it directly in your browser: [aquuamon.github.io/aimulator](https://aquuamon.github.io/aimulator/)

No installation required — just open the page, enter your DPI, and click anywhere to lock your cursor.

## Requirements

- A desktop browser (Chrome, Edge, or Firefox recommended)
- Keyboard and mouse — uses the **Pointer Lock API**, so touch devices are not supported

## Keybinds

| Key | Action |
|-----|--------|
| `Click` | Lock cursor |
| `ESC` | Release mouse / pause run |
| `U` / `I` | Sensitivity −/+ 0.005 |
| `R` | Restart minigame |

## Technology Stack

Built with vanilla **HTML, CSS, and JavaScript** — no frameworks, no build step, no dependencies:
- **Canvas API** for rendering
- **Pointer Lock API** for cursor capture
- **localStorage** for leaderboard persistence

## How It Was Built

Part hand-written code, part AI-assisted "vibe coding" with human design and decisions.

## License & Attribution

This project is licensed under the **Creative Commons Attribution-NonCommercial 4.0 International (CC BY-NC 4.0)**.

**You are free to:**
- ✅ Use the software for personal or educational purposes.
- ✅ Modify, adapt, and fork the code.
- ✅ Share the software with others.

**Conditions:**
- ⚠️ **Attribution**: You must give appropriate credit to the original author.
- ⚠️ **NonCommercial**: You may not use the material for commercial purposes without explicit permission.

> *Note: Commercial use (selling the tool, embedding it in a paid product/service) requires prior authorization from the author.*

For full legal terms, see the [LICENSE](LICENSE) file.

---

**Use at your own responsibility.**