# ECHOTRON

> **ORBITAL PULSE INDUSTRIES · 2041**

ECHOTRON is a minimalist arcade reflex game set in a cyberpunk dystopia. You are an operator — a signal being tested inside a collapsing neural network built by O.P.I, Orbital Pulse Industries. Navigate through an endless stream of expanding rings. Time your orbits. Pass through the gap. Don't get hit. Reach 100 rings and discover what you were really running from.

---

## Play

🎮 **[Play on GitHub Pages](https://syscolor.github.io/PULSE/)**

---

## Screenshots

![Menu Principal](https://github.com/user-attachments/assets/2b24fd4d-4dc1-4e4b-a134-ba34d56c6cd1)
![Gameplay](https://github.com/user-attachments/assets/42b40138-cbf6-4512-9b75-d6503d88a70c)
![Dark Mode](https://github.com/user-attachments/assets/05d45364-b2f5-4afc-8060-400ef23ff53b)
![O.P.I Store](https://github.com/user-attachments/assets/afb9cbad-476e-485f-ba36-2393f4e3d0d2)
![Achievements](https://github.com/user-attachments/assets/18d8b795-3b5a-4d37-b8ac-07a8027a5a2e)

---

## Gameplay

Rings expand outward from the center. Each ring has a gap — pass through it to score. Miss and you lose a life. Lose all four lives and the signal dies.

The game escalates automatically through 5 difficulty tiers:

| Tier | Description |
|---|---|
| `INIT` | Slow rings, wide gaps. Learn the system. |
| `TRACE` | Speed increases. Gaps tighten. |
| `BREACH` | Spinning rings appear. Gaps shrink. |
| `CRITICAL` | High pressure. Minimum margin. |
| `HELL_SYNC` | Maximum speed. Minimum mercy. |

Every 25 rings, the game pauses and offers a **Signal Upgrade** to choose from — making each run unique. As you pass rings, you unknowingly compose a full piano melody of 100 notes. It builds, peaks at ring 40, and resolves by ring 100.

---

## The Ending

Reach 100 rings and the game goes silent. No fanfare. No explosion.

The world slowly zooms out — your game world shrinks, then disappears. A dark O.P.I laboratory room fades in. A sleek industrial computer rises from a desk with your game frozen on its CRT screen. Your robot appears beside it, staring at the monitor. Text materializes slowly:

> `// it was just a simulation`

The camera then pulls back further to reveal the O.P.I headquarters tower at night, glowing windows across its facade. One window burns orange. A philosophical quote fades in from the dark:

> *"Freedom is not the absence of walls. It is the distance between you and the one who built them."*
> — O.P.I INTERNAL MEMO · 2041

---

## Secret Ending

During the apartment scene, there is one orange-lit window on the O.P.I tower. **Click it three times.**

A hidden pixel game opens. You control your robot escaping through the rain — past factory walls, dark streets, pixel crowds and O.P.I helicopters sweeping searchlights trying to find you. As the rain fades and the city disappears, you reach an open field. The sky brightens. Flowers grow. Your robot walks to the center and lies down.

Everything fades to black.

A piano melody begins — quiet, resolving, like something finally at peace.

A last line appears:

> *"Rest is not the end of the journey. It is the proof that you survived it."*
> — O.P.I FIELD LOG · 2041

---

## Features

- **Solo Extraction** — reach 100 rings to trigger the ending sequence
- **Signal Upgrades** — roguelike upgrade system exclusive to Solo mode
- **O.P.I Duel** — local 1v1 split-screen with sabotage mechanics
- **5 difficulty tiers** that escalate automatically
- **Procedural melody** — each ring pass plays the next note of a 100-note piano composition
- **Musical peak at ring 40** — volume spike, dissonant chord, particle burst
- **Visual climax at rings 50–75** — background pulses with the music
- **Skin system** with O.P.I Store — 4 operators + 1 secret, equipped independently for P1 and P2
- **Robot faces** — each operator has a unique animated eye, body shape, and personality
- **O.P.I Credits** — earned by playing, spent in the store
- **Combo multiplier** — chain rings for score bonuses
- **Shield overflow** — collecting a second shield converts to +1 life
- **Near-miss detection** — canvas flash and particles when you barely survive
- **Warning ring** — ghost arc previews the next gap position
- **Dot trail** — motion trail follows your operator at speed
- **Achievement system** — 8 unlockable achievements tracked across sessions
- **Dark mode** — toggleable, persisted across sessions
- **Contextual narrative** — dialogue reacts to what happens in real time
- **Procedural soundtrack** — 6 ambient tracks (3 menu + 3 battle) synthesized entirely with Web Audio API
- **Menu preview** — animated O.P.I building with robots orbiting and rings expanding on the right side of the menu
- **Terminal and cheat codes** — secret codes accessible in-game
- **CrazyGames SDK** integrated and compliant
- **Full mobile support** with touch controls
- **Responsive scaling** — adapts to any screen size

---

## Signal Upgrades *(Solo only)*

Every 25 rings the game pauses and offers 3 random upgrades. Each run is different — upgrades never repeat within a run and stack across choices.

| Category | Upgrade | Effect |
|---|---|---|
| ⚡ Mobility | `OVERCLOCK` | Move 25% faster |
| 〜 Mobility | `DRIFT` | Less friction — smoother orbit |
| ◎ Mobility | `SNAP ORBIT` | Orbit switch is instant |
| ▮ Survival | `EXTRA LIFE` | +1 life (max 5) |
| ✦ Survival | `SECOND CHANCE` | Survive one fatal hit |
| ◈ Survival | `GHOST SHIELD` | Next hit is ignored |
| ⬡ Score | `DOUBLE CREDITS` | O.P.I credits earned ×2 this run |
| × Score | `COMBO EXTEND` | Combo timer lasts 50% longer |
| ◉ Score | `RING MAGNET` | Gap size increased slightly |
| ★ Style | `OVERCHARGE` | Trail is longer and brighter |
| ◐ Style | `NEON` | Rings glow intensely |

---

## Operators

| Operator | Body | Eye | Color | Price | Notes |
|---|---|---|---|---|---|
| **FIZZ** | Rounded pill | White bar, blinks | Orange `#c84000` | Free | Default P1 |
| **SERAPH** | Sharp rectangle | Cold slit, never blinks | Blue `#0070aa` | 150 ⬡ | Default P2 |
| **VOID** | Diamond | Pulsing eye | Purple `#660099` | 300 ⬡ | Unlocks exclusive ending |
| **YAN** | Rectangle | RGB bar | Chromatic | 500 ⬡ | Full RGB rings |
| **MEQUINTOSHI** | Macintosh 128K | CRT screen face | Beige | Secret | Unlock via terminal |

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
| ↯ | `ROTOR` | ??? |

---

## Soundtrack

Six fully procedural ambient tracks synthesized in real time — no audio files, no external dependencies.

**Menu (3 tracks, random rotation):**
- Track 1 — Aria Math style: sparse piano, long silences, ethereal pad in Fm, vast reverb
- Track 2 — Hybrid: warm Moog pad in Cm with walking bass and ethereal piano above
- Track 3 — Moog City: sawtooth bass Am with vibrato, synth lead melody, most rhythmic of the three

**Battle (3 tracks, random rotation):**
- Track 1 — HFF Winter: glockenspiel, cutting wind, ice drone, D minor
- Track 2 — Häggström style: individual Am piano notes with very long sustain, sparse Moog bass
- Track 3 — Moog City battle: Am sawtooth pad, walking bass with vibrato, lead synth melody

Each ring pass triggers the next note of a 100-note piano melody in 4 phrases: intro → development → climax → resolution.

---

## Terminal Codes

Open the terminal with `[ TERMINAL ]` or during gameplay.

| Code | Effect |
|---|---|
| `BERRYBURN` | +1000 O.P.I Credits |
| `SKIP` | Jump to ring 99 |
| `1337` / `ROTOR` | Force HELL_SYNC |
| `PULSE2` | Restore all lives, exit hell mode |
| `GHOST` | Invincibility |
| `MATRIX` | Particle burst |
| `ONIX` | Unlock all achievements |
| `HOGHOG` | Force upgrade screen — 4 uses per run *(Solo only)* |
| `MESSIAS` | Unlock secret operator |
| `LISO LISO LISO` | Force maximum performance mode |
| `SEQUINHO` | Restore auto performance mode |

---

## Tech

- Pure **HTML + CSS + JavaScript** — single file, zero dependencies, zero build tools
- **Web Audio API** — 6 ambient tracks, procedural melody, rain sound, ending music, all synthesized
- **Canvas 2D** — all rendering, particles, rings, robot faces, dot trail, cinematic sequences
- **localStorage** — credits, skins, achievements, dark mode, best score, deaths, play history
- **CrazyGames SDK** — gameplayStart/Stop, mute handler, ad integration

---

## Structure

```
ECHOTRON/
├── index.html      # entire game — single file
├── README.md
└── LICENSE
```

---

## License

© 2026 Marzio. All rights reserved.
Original game created by Marzio. Unauthorized copying or redistribution is prohibited.
