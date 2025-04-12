# Roguelike Game

A simple roguelike game built with Python. This project includes grid-based movement, level generation, and basic enemy behavior using Pygame.

## 🎮 Features

- Player movement and controls
- Randomly generated levels
- Basic enemy AI
- Retro pixel-art style
- Lightweight and easy to extend

## 🗂️ Project Structure

```
.
├── main.py                 # Entry point for the game
├── src/
│   ├── game.py             # Game loop and core logic
│   ├── entity.py           # Player and enemy entity classes
│   ├── level.py            # Level generation and tile management
│   └── constants.py        # Game configuration and constants
└── assets/
    ├── fonts/
    │   └── pixel_font.ttf  # Retro-style font
    └── images/
        ├── player.png      # Player sprite
        ├── enemy.png       # Enemy sprite
        └── tile.png        # Tile/environment graphics
```

## 🛠 Requirements

- Python 3.7+
- Pygame

Install dependencies with:

```bash
pip install pygame
```

## 🚀 How to Run

From the project root directory, run:

```bash
python main.py
```

## 📦 Assets

All visual and audio assets used are either created by the developer or under open licenses.

## 📃 License

This project is licensed under the MIT License. See the `LICENSE` file for more info.

---

Happy dungeon crawling!
