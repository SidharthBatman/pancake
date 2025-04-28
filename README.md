# Space Pizza Hunter 🥞 - Terminal Game

**Space Pizza Hunter** is a terminal-based survival game built using Python's `curses` module.  
Your goal: collect food (`✿`) while avoiding enemies (`E`) in a randomly generated world.

## 🎮 How to Play

- **Controls:**
  - `W` – Move Up
  - `A` – Move Left
  - `S` – Move Down
  - `D` – Move Right
  - `Q` – Quit the game

- **Collect food (`✿`)** to increase your score.
- **Avoid enemies (`E`)** — getting caught ends the game.

## 🧠 Game Logic

- World is randomly generated with walkable paths and obstacles (`.`).
- Enemies chase the player with varying levels of accuracy.
- Food has a lifespan — it disappears and respawns if not collected.

## 🛠️ Requirements

- Python 3.x
- Terminal that supports `curses` (macOS/Linux. Windows needs `windows-curses` package)

### Windows Users

```bash
pip install windows-curses
