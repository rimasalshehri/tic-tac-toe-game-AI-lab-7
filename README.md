# tic-tac-toe-game-AI-lab-7
Objective: Apply and implement Minimax algorithm.  Activity Outcomes: An implementation of Minimax AI Algorithm on Tic-Tac-Toe.
Objective:
Apply and implement Minimax algorithm.

Activity Outcomes:
An implementation of Minimax AI Algorithm on Tic-Tac-Toe.
The game flow:
Let’s say the computer is represented by the character ‘O’ and the user is represented by ‘X’.
1.	Print the empty board.
2.	The computer makes the first move and the board is printed with an ‘O’ added to the slot that the algorithm picked.
3.	The user is prompted to pick a slot represented by a number.
4.	Once the user inputs a number, that slot is checked whether it’s empty or not, if it’s taken, an error is displayed and the user is prompted to pick another slot if the slot is empty, an ‘X’ is inserted there.
5.	The algorithm then plays with itself in the background, checking the score yielded by picking every available slot and finding the best move. Once the best move is found, it makes that move, prints out the board, and back to step 3.
