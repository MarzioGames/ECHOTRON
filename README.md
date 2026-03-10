# PULSE

> **NEURAL EXTRACTION PROTOCOL · 2041**

PULSE is a minimalist arcade reflex game set in a cyberpunk dystopia. You are CASTIEL — a rogue signal trying to escape a collapsing neural network before the system erases you.

Navigate your operator through an endless stream of expanding rings. Time your orbits. Pass through the gap. Don't get hit. Reach 100 rings and escape.

---

## Play

🎮 **[Play on GitHub Pages](https://syscolor.github.io/PULSE/)**

---

## Screenshots

![Menu Principal](https://github.com/user-attachments/assets/2b24fd4d-4dc1-4e4b-a134-ba34d56c6cd1)
![Gameplay](https://github.com/user-attachments/assets/42b40138-cbf6-4512-9b75-d6503d88a70c)
![Dark Mode](https://github.com/user-attachments/assets/05d45364-b2f5-4afc-8060-400ef23ff53b)
![Neural Store](https://github.com/user-attachments/assets/afb9cbad-476e-485f-ba36-2393f4e3d0d2)
![Conquistas](https://github.com/user-attachments/assets/18d8b795-3b5a-4d37-b8ac-07a8027a5a2e)

---

## Gameplay

Rings expand outward from the center of the screen. Each ring has a gap — pass through it to score. Miss the gap and you lose a life. Lose all three lives and the signal dies.

The game escalates automatically through 5 difficulty tiers:

| Tier | Description |
|---|---|
| `INIT` | Slow rings, wide gaps. Learn the system. |
| `TRACE` | Speed increases. Gaps tighten. |
| `BREACH` | Spinning rings appear. Gaps shrink further. |
| `CRITICAL` | Shrinking gaps. Higher pressure. |
| `HELL_SYNC` | Maximum speed. Minimum mercy. |

---

## Features

- **Solo Extraction** — reach 100 rings to trigger the escape sequence
- **Signal Upgrades** — roguelike upgrade system exclusive to Solo mode
- **Neural Duel** — local 1v1 split-screen with sabotage mechanics
- **5 difficulty tiers** that escalate automatically based on score
- **Skin system** with Neural Store — 3 operators, P1 and P2 equipped independently
- **Neural Credits** — earned by playing, spent in the store
- **Combo multiplier** — chain rings for score bonuses
- **Shield overflow** — collecting a second shield converts to +1 life
- **Near-miss detection** — canvas flash + particles when you barely survive
- **Warning ring** — ghost arc previews incoming ring gap position
- **Dot trail** — motion trail follows your operator at speed
- **Achievement system** — 7 unlockable achievements tracked across sessions
- **Dark mode** — toggleable via `[ ◑ ]` button, persisted across sessions
- **Contextual narrative** — dialogue reacts to what happens in real time
- **Procedural audio** — full soundtrack built with Web Audio API, zero audio files
- **Terminal / Cheat codes** — secret codes accessible in-game
- **CrazyGames SDK** integrated and compliant
- **Full mobile support** with touch controls
- **Responsive scaling** — adapts to any screen size

---

## Signal Upgrades *(Solo only)*

Every 25 rings the game pauses and offers 3 random upgrades to choose from. Each run is different — upgrades never repeat within a run and stack across choices.

| Category | Upgrade | Effect |
|---|---|---|
| ⚡ Mobility | `OVERCLOCK` | Move 25% faster |
| 〜 Mobility | `DRIFT` | Less friction — smoother orbit |
| ◎ Mobility | `SNAP ORBIT` | Orbit switch is instant |
| ▮ Survival | `EXTRA LIFE` | +1 life (max 5) |
| ✦ Survival | `SECOND CHANCE` | Survive one fatal hit with 1 life |
| ◈ Survival | `GHOST SHIELD` | Next hit is ignored |
| ⬡ Score | `DOUBLE CREDITS` | Neural credits earned ×2 this run |
| × Score | `COMBO EXTEND` | Combo timer lasts 50% longer |
| ◉ Score | `RING MAGNET` | Gap size increased slightly |
| ★ Style | `OVERCHARGE` | Trail is longer and brighter |
| ◐ Style | `NEON` | Rings glow intensely |

---

## Operators

| Operator | Color | Ring Style | Price | Notes |
|---|---|---|---|---|
| **CASTIEL** | Orange `#c84000` | Solid | Free | Default P1 |
| **S.I.M.O.N.** | Blue `#0070aa` | Dashed | 150 ⬡ | Default P2 |
| **VOID** | Purple `#660099` | Pulsing | 300 ⬡ | Unlocks exclusive ending |

Playing as VOID and completing Solo Extraction triggers a unique ending sequence.

---

## Controls

| Action | P1 | P2 |
|---|---|---|
| Move | `A` / `D` | `←` / `→` |
| Orbit inward | `SPACE` | `SHIFT` |
| Orbit outward | `S` | `↓` |
| Pause | `ESC` | — |
| Mute | `M` | — |

---

## Achievements

| Icon | Name | Condition |
|---|---|---|
| ◈ | `GHOST` | Pass 5 rings without moving |
| ✦ | `FLAWLESS` | Complete extraction with full HP |
| ⚡ | `HELL SURVIVOR` | Pass 20 rings in HELL_SYNC |
| ◉ | `VOID TOUCHED` | Play as the VOID operator |
| × | `COMBO MASTER` | Reach ×10 combo |
| ▣ | `UNTOUCHABLE` | Pass 15 rings in a row |
| 💀 | `SERIOUSLY?` | Die 100 times |

All achievements are tracked across sessions via `localStorage`.

---

## Terminal Codes

Open the terminal with `[ TERMINAL ]` button or during gameplay. Type a code and press `Enter`.

| Code | Effect |
|---|---|
| `BERRYBURN` | +1000 Neural Credits |
| `SKIP` | Jump to ring 99 |
| `1337` / `ROTOR` | Force HELL_SYNC |
| `PULSE2` | Restore all lives, exit hell mode |
| `GHOST` | Invincibility |
| `MATRIX` | Particle burst |
| `ONIX` | Unlock all achievements |
| `HOGHOG` | Force upgrade screen — 4 uses per run *(Solo only)* |
| `LISO LISO LISO` | Force maximum performance mode |
| `SEQUINHO` | Restore auto performance mode |

---

## Tech

- Pure **HTML + CSS + JavaScript** — single file, zero dependencies, zero build tools
- **Web Audio API** — procedural drone, hit sounds, score tones, victory fanfare
- **Canvas 2D** — all rendering, particles, rings, dot trail
- **localStorage** — credits, skins, achievements, dark mode, best score
- **CrazyGames SDK** — gameplayStart/Stop, mute handler, ad integration

---

## Structure

```
PULSE/
├── index.html      # entire game — single file
├── README.md
└── LICENSE
```

---

## License

© 2026 Marzio. All rights reserved.  
Original game created by Marzio. Unauthorized copying or redistribution is prohibited.
