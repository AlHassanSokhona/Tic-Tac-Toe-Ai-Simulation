This project is a console-based implementation of Tic-Tac-Toe in C++ featuring an intelligent computer opponent that is designed to never lose.
Instead of relying on random moves, the computer evaluates the board state and makes strategic decisions to win when possible or force a tie otherwise.

Features:
Smart AI opponent using rule-based decision making
Deterministic gameplay (no randomness)
User-friendly console UI with numbered positions (1–9)
Guaranteed win or tie for the computer when playing first
Fully compatible with ZyBooks / standard C++ environments

The Ai Strategy
The computer determines its move using the following priority order:
Win if possible – completes a three-in-a-row if available
Block opponent – prevents the human player from winning
Take the center – strongest strategic position
Take a corner – increases future winning opportunities
Take any available space – fallback option
This approach ensures optimal play without requiring recursion or minimax algorithms

The game uses a clean ASCII-based board layout where empty spaces are labeled from 1–9:
Players select a move by entering the corresponding number, making the game intuitive and easy to play in a terminal environment.
 
 1 | 2 | 3

 4 | 5 | 6     

 7 | 8 | 9
 
 Ai always plays first
