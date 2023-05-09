# MatrixGame
The code is a Java program that simulates a football game

# Discription
This is a matrix game where the user controls a football player to reach the bottom right of a matrix while avoiding obstacles represented by '*' characters. The program has different levels of difficulty, and the user can move the football player using the keyboard arrow keys. The program keeps track of the number of times the user fails to move the ball and ends the game if the user exceeds five failures or reaches the target.

Here's a brief overview of what the code does:

The program starts by prompting the user to select a difficulty level (easy, medium, or hard) and creates a matrix based on the chosen difficulty level.

It then calculates the shortest path from the starting position to the target position in the matrix using the "shortestPathToTarget" method, which employs a recursive algorithm to calculate the steps required.

After displaying the shortest path to the target, the program prompts the user to move the football player using the keyboard arrow keys.

The program then enters a loop where the user is prompted to move the football player until they either reach the target or fail to move the ball five times.

The program tracks the position of the football player and the ball using the "rightFoot" and "ball" arrays, respectively. The program then checks if the user's move is valid by checking if the ball can be moved in the desired direction without hitting any obstacles. If the move is invalid, the program increments a counter and ends the game if the counter exceeds five.

If the user reaches the target, the program prints a congratulatory message.
