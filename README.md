# Sum Puzzle Game

This repository contains a simple HTML/JavaScript puzzle game. The goal is to mark the digits that contribute to the sums shown on the right and bottom edges of the grid.

## Running
Open `index.html` in any modern web browser. No build step or server is required.

## Gameplay
1. On the start screen choose the grid width, height, difficulty level and an optional seed.
2. Press **Start Puzzle** to generate and play.
3. Click a cell to cycle between unmarked, marked as correct (green) and marked as incorrect (red).
4. When every cell is marked and all correct numbers are identified the timer stops and a result screen is shown.
5. From the result screen you can start a new puzzle.

The puzzle generation uses a seeded pseudo random generator so the same seed and settings will recreate the same puzzle.
