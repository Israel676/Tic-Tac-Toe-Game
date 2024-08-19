# Tic-Tac-Toe Game Documentation
# Overview
The Tic-Tac-Toe game is a simple console-based application written in C that allows two players to play the classic 3x3 grid game. The players take turns to mark a cell with their respective symbols (X or O). The game continues until one player wins or the grid is filled, resulting in a draw.

# Features
Two-player mode with alternating turns.
Dynamic game board that updates after each move.
Input validation to prevent invalid or repeated moves.
Automatic detection of winning conditions and draw scenarios.
# Requirements
Operating System: Windows, Linux, or macOS
Compiler: Any C compiler (e.g., GCC, Clang, MSVC)
# Files
tictactoe.c: The source code file containing the implementation of the game.
# How to Compile and Run
# Compile
To compile the game using GCC (or another C compiler), open a terminal and navigate to the directory containing the tictactoe.c file. Then run:

bash
gcc -o tictactoe tictactoe.c
This command will compile the code and create an executable named tictactoe.

# Run
To start the game, use the following command:

bash
./tictactoe