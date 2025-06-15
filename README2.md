# Tic-Tac-Toe Game (Java Console Application)

## Overview

This is a simple **Tic-Tac-Toe** game built in Java for two players to play on the same computer. It runs in the console and allows players to take turns entering their moves on a 3x3 grid.

## Features

- Two-player mode (`X` vs `O`)
- Input validation for moves
- Automatic check for win or draw conditions
- Clear display of the board after each move

## How to Run

1. **Compile the Java file**:


2. **Run the program**:


3. **Gameplay instructions**:

- Players take turns.
- Enter the row and column number (0 to 2) for your move.
- The game ends when one player wins or it's a draw.

## Example


## Win Condition

The game checks after every move:
- All rows
- All columns
- Both diagonals

If any of them contain three same non-empty symbols (`X` or `O`), the current player wins.

## Draw Condition

If all 9 cells are filled and no one has won, the game ends in a draw.

## Requirements

- Java 8 or above
- No external libraries needed

## Author

*Your Name Here*
