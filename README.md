# Tic-Tac-Toe 🎮

A simple two-player Tic-Tac-Toe game built with Python and Tkinter.

## Requirements

- Python 3.x
- Tkinter (included in most standard Python installations)

## How to Run

```bash
python tictactoe.py
```

## How to Play

1. The game starts with **Player X**'s turn.
2. Players take turns clicking any empty cell on the 3×3 grid.
3. The first player to get **three in a row** (horizontally, vertically, or diagonally) wins.
4. If all 9 cells are filled with no winner, the game ends in a **tie**.
5. Winning cells are highlighted in **green**.

## Features

- Two-player local multiplayer (X and O)
- Turn indicator label that updates after each move
- Win detection for all rows, columns, and diagonals
- Tie detection when the board is full
- Winning combination highlighted in green
- Pop-up messages announcing the winner or a tie

## Project Structure

```
tictactoe.py   # Main game file
README.md      # This file
```

## Controls

| Action        | How                        |
|---------------|----------------------------|
| Make a move   | Click an empty grid cell   |
| Restart       | Close and rerun the script |
