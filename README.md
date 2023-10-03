# Minesweeper Game

## Description

This Python program implements a simple text-based Minesweeper game. It consists of three main classes: `GamePlay`, `Board`, and `MSSquare`, which manage the gameplay, board setup, and square properties respectively.

## Usage

To play the game, run the `minesweeper.py` file. Follow the prompts to choose the board size and the number of mines. Input coordinates to sweep the mines. The game continues until you either win or lose.

## Classes

### GamePlay

- Manages the player's input with the game board.
- Contains methods for checking win condition, handling player moves, and exposing the board.

### Board

- Sets up the terms of the game, including board size and number of mines.
- Creates the game board matrix and handles populating mines and adding neighbors.

### MSSquare

- Represents a single square on the game board.
- Contains properties for whether it has a mine, is hidden, and the number of neighboring mines.

## How to Play

1. Run the `minesweeper.py` file.
2. Choose the board size (4 - 9) and the number of mines (1 - 2 * size).
3. Enter your name.
4. Input coordinates (n, m) to sweep the mines.
5. Continue until you either win or lose.
6. Optionally, choose to play another game.

## Example

```python
python minesweeper.py
