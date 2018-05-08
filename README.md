# riddle_maze
Code for CS50 final project
In order to use this project, you will need to have installed Python 3, the latest version of Tkinter, as well as
Pygame.
You will need to download the riddle_maze directory in its entirety. In order to play the game, run maze_game.py.
The goal of the came is to get to the bottom right hand corner of the screen.
On the maze you will see your sprite, a red box, and a riddle sprite, a green box. If you touch the green box, a riddle
should pop up. However, given an unfound bug that is not the case. In order to see what should popup, please run
riddle_noClass.py. This is essentially the same thing as riddles.py but rather than being a class, it is independent
and can stand on its own.
To see how the user sprite and background are drawn, please see starter.py. In this, I use pygame to set the background
image, as well as move the user sprite, preventing it from going through any walls of the maze or from passing through
the riddles.
The image/sprite for the riddles is contained in riddles.py. However, given that riddles.py is not compeltely
functioning, I will explain how the riddles work using riddle_noClass.py. A tkinter window shows up asking the player
a question. The player types in their answer and after clicking a button, the answer shows up. The user then has the
option to receive a new riddle (closing the window of the previous window).
Touching a riddle sprite while playing (ie running maze_game.py) leads to a crash. However, the user is unable to pass
through walls, and in riddle_noClass.py, the riddle-answer function works fine.
