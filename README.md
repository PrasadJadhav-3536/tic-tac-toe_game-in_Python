# tic-tac-toe_game-in_Python
Create a Tic-Tac-Toe game in Python: Set up the board, display it, get player input, update the board, check for a win or draw, alternate turns, repeat until a winner or draw, print the outcome.

Here's a step-by-step description of how you can create a simple Tic Tac Toe game using Python:

1.Start by creating a 3x3 grid to represent the game board. You can use a list of lists to represent the grid, where each element represents a cell on the board. Initialize all the elements with an empty string, indicating an empty cell.

2.Create a function to display the game board. You can iterate through the grid and print the current state of each cell, using appropriate symbols for X, O, and empty cells.

3.Write a function to handle player input. Prompt the player to enter the row and column they want to place their symbol in. Validate the input to ensure it's within the range of the grid and the selected cell is empty.

4.Implement a function to check for a win condition. Iterate through the grid and check if there are three symbols in a row, horizontally, vertically, or diagonally. If a win condition is met, declare the player who made the winning move as the winner.

5.Create a main game loop that alternates between players. In each iteration, display the game board, handle player input, update the grid with the player's symbol, and check for a win condition. If a win condition is met or the grid is full (indicating a tie), end the game.

6.Optionally, you can add a replay option to allow players to restart the game after it ends.
