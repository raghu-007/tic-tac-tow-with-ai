# tic-tac-tow-with-ai

This TICTACTOE project is written in Python. The project file contains the python script (tic-tac-tow.py). This is a python implementation of the paper-and-pencil game from childhood: Tic-Tac-Toe, also known as Noughts and crosses or Xs and Os. This program implements the game for two-player. All the playing rules are the same just like we play in real-time tic-tac-toe.

About the Project
This game is simply in command line with python 3. The gameplay design is so simple that the user won’t find it difficult to use and understand. It is possible to play the game with the AI, with three levels. The “easy” level will make random moves. The “medium” level difficulty makes a move using the following process:

If it can win in one move (if it has two in a row), it places a third to get three in a row and win. 2. If the opponent can win in one move, it plays the third itself to block the opponent to win. 3. Otherwise, it makes a random move.
The “hard” level difficulty implements the minimax algorithm, which is the brute force algorithm that maximizes the value of the own position and minimizes the value of the opponent’s position. Basically, it can see all possible outcomes till the end of the game and choose the best of them considering his opponent also would play perfectly. So, it does not rely on the blunders of the opponent, it plays perfectly regardless of the opponent’s skill.

The main menu accepts two commands: “start” and “exit“. The “start” command takes two parameters: four parameters are possible: “user” to play as a human, and “easy“, “medium” and “hard” to play as an easy level AI. The command “exit” should simply terminate the program.

The first player uses the “X” symbol, the second “O”. If any of the player is human, the user should input 2 numbers that represent the cell on which user wants to make his “X” or “O”.

How To Run The Project?
To run this project, you must have installed Python on your PC. After downloading the project, follow the steps below:

Step1: Extract/Unzip the file

Step2: Go inside the project folder, open cmd then type tic-tac-tow.py and enter to start the system.

OR

Step 2: Simply, double click the tic-tac-tow.py file and you are ready to go.
