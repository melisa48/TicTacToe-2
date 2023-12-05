# TicTacToe-2
Tic Tac Toe Game
This is a console-based Tic Tac Toe game implemented in C++. It allows two players to take turns marking spaces on a 3x3 grid, and the game continues until one player wins or the board is full (resulting in a draw).

How to Play
Run the program.
Players take turns entering a number corresponding to the cell where they want to place their mark.
The game alternates between "X" and "O" marks for Player 1 and Player 2, respectively.
The game ends when one player wins by having three of their marks in a row horizontally, vertically, or diagonally, or when the board is full (resulting in a draw).
Example Gameplay
plaintext
Copy code
Tic Tac Toe

Player 1 (X)  -  Player 2 (O)

     |     |     
  1  |  2  |  3  
_____|_____|_____
     |     |     
  4  |  5  |  6  
_____|_____|_____
     |     |     
  7  |  8  |  9  
     |     |     

Player 1, enter a number: 1

     |     |     
  X  |  2  |  3  
_____|_____|_____
     |     |     
  4  |  5  |  6  
_____|_____|_____
     |     |     
  7  |  8  |  9  
     |     |     

...

==>Player 1 win
Features
Simple and intuitive gameplay.
Dynamic updating of the game board.
Win-checking logic for horizontal, vertical, and diagonal alignments.
Draw detection when the board is full.
