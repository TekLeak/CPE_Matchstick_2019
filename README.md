# CPE_Matchstick_2019
Leave the last matchstick !

For this project, the only authorized function are read, write, malloc, free, time, getpid, random,srandom and getline.
This project is based on a very famous game based on matchsticks.
There is a certain number of matchstick lines. The two players take turns; each player can, on a same line, take one or several matchsticks. The losing player is the one to take the last matchstick.

The goal of the project is to create a program that you can play against.
The basic version must generate a game board with n matchstick lines (1 < n < 100) and have a simple interface so that the user could play against the computer.
The number of lines is given as parameter to the program.
The second parameter of the program indicates the maximum number of matches that can be taken out each turn (must be > 0).

When matchsticks are removed, they must be removed starting from the right (like in the example below). 
The user will always start the game.
The program’s output (error messages included) must correspond to the examples below. Error messages which happens during a game and which are destined to the player must be displayed on the standard output.

In case of bad input, you must ask for the line by displaying “Line:” again, and it’s up to the player to indicate again the line he/she wants to play on.
If the user wins, the program must return 1.
If the AI wins, it must return 2.

Here is a list of bonuses you may implement (in the bonus, built with a separate Makefile’s rule):
- a graphical interface,
- a more complete game, with score and several levels of difficulty,
- a human-machine interface device (such as a leap motion for instance) to select and remove the matchsticks.
