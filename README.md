# Minesweeper AI

This project implements an AI to play Minesweeper. It is based on the assignment provided by [CS50AI](https://cs50.harvard.edu/ai/2020/projects/1/minesweeper/).

![Minesweeper](https://cs50.harvard.edu/ai/2020/projects/1/minesweeper/images/game.png)
## Introduction

Minesweeper is a classic puzzle game where the player needs to uncover all the safe cells on a grid without detonating any hidden mines. Each cell in the grid can either be revealed, flagged as a mine, or untouched. The player wins when all safe cells are revealed and loses if they uncover a mine.

## Requirements

- Python 3
- Pygame library

## Getting Started

1. Clone this repository to your local machine:
   ```
   git clone https://github.com/diandrarad/minesweeper.git
   ```
2. Navigate to the project directory:
   ```
   cd minesweeper
   ```
3. Install the required Python package using:
   ```
   pip3 install -r requirements.txt
   ```
4. Run the game:
   ```
   python3 main.py
   ```

## Project Structure

- **minesweeper.py**: Contains the logic for the Minesweeper game and the MinesweeperAI class.
- **main.py**: Implements the graphical interface for the game and runs the game loop.
- **assets/**: Contains images and font used in the graphical interface.

## Implementation

The project involves completing the implementation of the `Sentence` class and the `MinesweeperAI` class in `minesweeper.py`.

### Sentence Class

The `Sentence` class represents a logical sentence containing a set of cells and a count of how many of those cells are mines. It provides methods to determine known mines, and known safes, mark a cell as a mine, and mark a cell as safe.

### MinesweeperAI Class

The `MinesweeperAI` class implements an AI player for Minesweeper. It keeps track of moves made, known mines, known safes, and knowledge about the game board. The AI makes decisions based on available knowledge to uncover safe cells and avoid mines.

## How to Play

- Left-click on a cell to reveal it.
- Right-click on a cell to mark it as a mine.
- Mark all mines correctly to win the game.

## Credits

This project is based on the Minesweeper assignment from [CS50AI](https://cs50.harvard.edu/ai/2020/projects/1/minesweeper/). Special thanks to CS50AI for providing the project specifications and resources.
