# Half-Gammon
A terminal-based two-player board game built in C++ based on a simplified version of Backgammon. Players take turns rolling a die and moving checkers across a 16-space board, with full support for bumping, re-entry, and bearing off mechanics.
Features

Two-player turn-based gameplay in the terminal
Checker bumping — land on an opponent's lone piece to send it off the board
Re-entry system — bumped checkers must re-enter before other moves can be made
Bearing off — first player to remove all checkers wins
Random die rolling powered by a Mersenne Twister algorithm
Input validation and quit functionality

Built With:
------------
C++
Mersenne Twister random number generator

How To Play
------------
Enter a seed when prompted to start the game
Enter the position number of the checker you want to move
Bumped checkers must re-enter the board before any other move
Enter -1 to quit at any time
First player to bear off all checkers wins
