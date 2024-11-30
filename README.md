# Dinosaur Game

Welcome to the "Dinosaur Game"! This is a simple browser-based game where you control a dinosaur to jump over obstacles and achieve the highest score.

## Features

- Jump over randomly generated obstacles.
- Track your score and game time.
- Responsive game controls.
- Playable directly in a web browser.

## How to Play

1. Open the game in your browser by opening the `index.html` file.
2. Press the **Spacebar** to start the game.
3. Use the **Spacebar** to make the dinosaur jump over obstacles.
4. Avoid colliding with obstacles to keep the game going.
5. When the game ends, press the **Spacebar** again to restart.

## Project Structure

```
Dinosaur Game
├── index.html   # Main HTML file containing the game.
├── styles.css   # CSS for styling the game (embedded in HTML).
├── audio        # Folder for game sounds.
│   ├── game-start.wav
│   └── jump.wav
└── README.md    # Project documentation.
```

## Customization

- **Dinosaur Appearance:**
  - Modify the `dino` object in the script to change its size or color.

- **Obstacle Settings:**
  - Adjust the `OBSTACLE_SPEED` variable to change obstacle speed.

- **Gravity and Jump:**
  - Modify `GRAVITY` and `JUMP_STRENGTH` to change the physics of the dinosaur's jump.

## Requirements

- A modern web browser (Chrome, Firefox, Edge, etc.).
- Internet connection for fonts (uses Google Fonts).

## Sounds

The game includes the following sound effects:

- **game-start.wav:** Played when the game starts.
- **jump.wav:** Played when the dinosaur jumps.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/dinosaur-game.git
   ```

2. Open the `index.html` file in your preferred browser.

## Contributions

Feel free to contribute by creating pull requests. Suggestions and improvements are welcome!

## License

This project is open-source and available under the MIT License. See the `LICENSE` file for details.

