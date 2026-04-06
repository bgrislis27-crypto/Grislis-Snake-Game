# Snake Game

A simple browser-based Snake game.

## How to play

1. Open `index.html` in your browser.
2. Use the Arrow Keys or WASD to move the snake.
3. Collect the red food pieces to grow longer.
4. Avoid colliding with the walls or the snake's own body.
5. Press `Space` to restart after game over.

## Notes

- The snake grows each time it eats food.
- The game speeds up gradually as your score increases.

## How it works

- The page uses an HTML canvas to draw the snake and food.
- JavaScript keeps track of the snake body as a list of grid cells.
- Each frame, the game moves the snake, checks collisions, and redraws the board.
- Arrow keys or WASD control the snake direction.
- If the snake hits a wall, obstacle, or its own body, the game ends.
- The play area shrinks over time (battle royale style), and random obstacles spawn.
- Press `Space` to restart after a game over.
