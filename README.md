# Grizzo's Snake Game

An arcade-style browser Snake game with custom settings, power-ups, dynamic hazards, and leaderboard tracking.

## How to Play

1. Open `index.html` in your browser.
2. Click **Start Game** on the menu screen.
3. Use **Arrow Keys** or **WASD** to control the snake.
4. Eat fruit to grow and increase your score.
5. Avoid collisions with walls, obstacles, and your own body.
6. After a game over, press **Space** to return to the menu and start again.

## Game Features

- **Custom game setup:** choose game mode, speed, snake color, and snake type.
- **Two modes:** Classic and Dynamic (shrinking safe area and obstacle spawning).
- **Power-ups:** speed boost, invincibility, and score boost.
- **Combo scoring:** earn more points with consecutive food pickups.
- **Visual effects:** animated grid, particles, power-up effects, and snake style variants.
- **Leaderboard:** save top scores in-browser with player names.

## Controls

- **Move up:** `ArrowUp` or `W`
- **Move down:** `ArrowDown` or `S`
- **Move left:** `ArrowLeft` or `A`
- **Move right:** `ArrowRight` or `D`
- **Return to menu after game over:** `Space`

## Technical Overview

- Built in a single `index.html` file using HTML, CSS, and vanilla JavaScript.
- Uses an HTML canvas for rendering gameplay.
- Stores snake body positions as grid coordinates and updates in a frame loop.
- Runs the game loop with `requestAnimationFrame`, with speed-based update timing.
- Persists high score and leaderboard data with `localStorage`.
