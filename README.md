# HTML5 Pacman Game

A minimalist Pacman clone built with HTML5 Canvas and vanilla JavaScript, featuring classic gameplay mechanics without the traditional maze structure.

## What It Does

This is a simplified Pacman game where the player navigates an open field, collecting power-ups while avoiding two AI-controlled ghosts. When a power-up is consumed, the ghosts become vulnerable and can be eaten for points. The game features:

- **Open-field gameplay** - No walls or traditional maze structure
- **Smart ghost AI** - Ghosts actively pursue the player with randomized movement patterns
- **Power-up system** - Collect white dots to temporarily turn ghosts vulnerable
- **Screen wrapping** - Move off one edge to appear on the opposite side
- **Real-time scoring** - Track your score vs the ghosts

## 🛠 Tech Stack

| Technology | Purpose |
|------------|---------|
| 🌐 HTML5 Canvas | 2D graphics rendering |
| ⚡ JavaScript (ES5) | Game logic and controls |
| 🎨 Base64 Sprites | Embedded character graphics |
| 🎮 Keyboard API | Arrow key input handling |

## How to Play

1. **Movement**: Use arrow keys to control Pacman
   - ⬅️ Left Arrow: Move left
   - ➡️ Right Arrow: Move right  
   - ⬆️ Up Arrow: Move up
   - ⬇️ Down Arrow: Move down

2. **Objective**: 
   - Avoid the red ghosts to prevent losing points
   - Collect white power-up dots to make ghosts vulnerable (blue)
   - Eat vulnerable ghosts to gain points
   - Survive as long as possible!

## Getting Started

Simply open `index.html` in any modern web browser. No installation or build process required.

```bash
# Clone the repository
git clone https://github.com/stabgan/html-pacman.git

# Open in browser
open index.html
```

## Game Features

- **Animated Pacman** with mouth opening/closing
- **Two ghost enemies** with independent AI
- **Collision detection** between all game objects
- **Power-up mechanics** with temporary invincibility
- **Score tracking** (Player vs Ghosts)
- **Responsive controls** with smooth movement

## ⚠️ Known Issues

- **Mobile compatibility**: Not optimized for touch screens (keyboard controls only)
- **No pause functionality**: Game runs continuously once started
- **No game over screen**: Scoring continues indefinitely

## Future Enhancements

- Add virtual touch controls for mobile devices
- Implement maze walls and traditional Pacman level design
- Add sound effects and background music
- Create multiple difficulty levels
- Add high score persistence

---

*A simple yet engaging take on the classic Pacman formula, perfect for learning HTML5 Canvas game development.*
