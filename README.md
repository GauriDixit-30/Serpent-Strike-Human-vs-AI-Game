# Serpent-Strike-Human-vs-AI-Game
Welcome to **Serpent Strike**, an exciting browser-based **Javascript** game where a human player competes head-to-head against a smart AI in a classic Snake game. This project explores game logic, real-time rendering, and simple artificial intelligence — all in one fun and challenging package!

## 🎮 Game Features

- 👤 **Player Mode** – Control your snake using arrow keys.

- 🤖 **AI Opponent** – Watch the AI play against you in real-time.

- 🍎 **Food Mechanics** – Eat food to grow and score points.

- 💥 **Collision Logic** – Game over if you hit the walls, yourself, or the opponent.

- 🔊 **Sound Effects** – Immersive feedback for actions and events.

- 🌟 **Visual Effects** – Smooth animations and particle effects for enhanced experience.

## 🚀 How to Play

1. Clone or download this repository:
   ```bash
   git clone https://github.com/your-username/serpent-strike.git
   cd serpent-strike

>Open index.html in any modern browser.

>Use arrow keys to move your snake. Avoid collisions and outsmart the AI!

## 🛠️ Tech Stack
>HTML5 & CSS3

>JavaScript (Vanilla)

>Canvas API for rendering

>Custom-built AI logic

## 📁 File Structure
```bash
Serpent Strike/
├── index.html             # Main game file

├── style.css              # Game styling

├── main.js                # Game loop and initialization

├── snake.js               # Player and AI snake logic

├── food.js                # Food mechanics

├── ui.js                  # UI updates

├── sounds.js              # Sound controls

├── particles.js           # Visual effects

├── audios/                # Sound assets
```

## 🧠 AI Strategy
The AI uses a basic pathfinding logic to move toward the food while avoiding walls and the player. Future improvements can include:

>A* or BFS pathfinding

>Prediction of player movements

>Obstacle-aware navigation
