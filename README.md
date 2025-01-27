# Game-2048

# Description

This project is a JavaScript implementation of the popular 2048 game. The game allows players to combine tiles by moving them in four directions (left, right, up, or down) to reach the goal of creating a tile with the value 2048.

The game includes all core mechanics of the original 2048, such as merging tiles, spawning new tiles, and managing win/loss conditions. The user interface is interactive and responsive, providing a seamless gaming experience.

# Features

Game Field: A 4x4 grid where the game takes place.
Tile Movement: Tiles move and merge based on the player’s arrow key inputs.
Random Tile Generation: After every move, a new tile with a value of 2 or 4 is generated in a random empty cell (with a 10% probability for 4).
Scoring System: The score increases with every successful merge, reflecting the sum of the merged tiles.
Win Condition: The game ends with a win when a tile reaches 2048.
Game Over Condition: The game ends with a loss when no more valid moves are possible.
Restart Button: Resets the game to the initial state.
Dynamic UI: Updates the grid and score in real-time as the game progresses.
Keyboard Controls: Handles player input via arrow keys for smooth gameplay.

# How to Play

Use the arrow keys (←, ↑, →, ↓) to move the tiles.
Tiles with the same value merge into one when they collide, forming a tile with double the value.
Aim to create a tile with the value of 2048 to win the game.
The game ends if there are no more valid moves.
Technologies Used
JavaScript (ES6+): Core game logic and interactivity.
HTML: Structure of the game board and UI elements.
CSS: Styling for the game grid, tiles, and overall design.

# Play the Game

- [DEMO LINK](https://kostiukmkalne.github.io/js_2048_game/)
