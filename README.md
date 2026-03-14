# 🟡 HTML Pac-Man

A browser-based Pac-Man clone built with HTML5 Canvas and vanilla JavaScript. No frameworks, no dependencies — just open and play.

## What It Does

A simple Pac-Man game where you navigate the board, avoid two ghosts, and collect power-up dots. Eating a power-up lets you chase and eat the ghosts temporarily (they turn blue and flee). The score tracks Pac-Man kills vs Ghost kills.

- Arrow keys to move
- Screen wraps around (go off one edge, appear on the other)
- Power-ups spawn periodically — grab them to turn the tables on the ghosts
- Ghosts chase you with semi-random AI movement patterns

## How to Play

Open `index.html` in any modern browser. That's it.

```bash
# or serve it locally
npx serve .
```

## 🛠 Tech Stack

| Tech | Purpose |
|------|---------|
| 🌐 HTML5 | Page structure |
| 🎨 Canvas API | Game rendering via `ctx.drawImage` with sprite sheet |
| ⚡ JavaScript (ES6+) | Game logic, collision detection, animation loop |

## Project Structure

```
├── index.html   # Full game (HTML + JS + embedded sprite sheet)
├── pac.png      # Sprite sheet source image
└── README.md
```

## ⚠️ Known Issues

- Keyboard-only — no touch/mobile support (virtual buttons could be added)
- No walls or food pellets — it's a simplified arena-style Pac-Man
- No game-over or win condition — the score just keeps going
- Ghost AI is basic random movement that loosely tracks the player
