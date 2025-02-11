# Tic-Tac-Toe
This project implements the classic two-player game Tic-Tac-Toe using Python. The game board is made of nine cells numbered from 1 to 9, which players mark alternately with an 'O' or an 'X'. The goal is to be the first to mark three 'O's or 'X's diagonally, horizontally, or vertically. The code base utilizes Python's object-oriented programming, defining a TicTacToe class with attributes and methods to represent the game's features. The Python random module is employed to randomly select the first player.

## Project Structure
The core of this project is a single Python file, tictactoe.py. It contains the TicTacToe class with its associated attributes and methods.

Here is a brief overview of the class methods:

__init__() initializes the game board and randomly selects the first player.

get_random_first_player() chooses whether 'X' or 'O' will play first.

fix_spot() allows a player to mark a cell on the board.

has_player_won() checks if a player has won the game.

is_board_filled() checks if the game board is completely filled.

swap_player_turn() toggles the active player.

show_board() prints out the current state of the game board.

start() begins the game loop, processing user input and game updates.

## Requirements
To run this project, you will need:

Python 3.x
The project also assumes that you have a basic understanding of Python programming and object-oriented programming concepts.
