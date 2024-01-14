# Tic Tac Toe Game

## Overview

Tic Tac Toe is a classic two-player game where the objective is to create a line of three of your symbols (either "X" or "O") horizontally, vertically, or diagonally on a 3x3 grid. Players take turns marking an empty cell with their symbol, and the first to achieve a line wins the game. If the grid is filled and no player has a line, the game is a draw.

## Requirements

To create a simple Tic Tac Toe game using Python, you'll need the following:

- Python installed on your machine (version 3.x is recommended).

## How to Make


1. **Create the Game Board:**
   Start by creating a 3x3 grid to represent the game board. You can use a list of lists to achieve this.

   ```python
   board = [
       [' ', ' ', ' '],
       [' ', ' ', ' '],
       [' ', ' ', ' ']
   ]
2. **Display The Board**
    ```python
    def display_board():
        for row in board:
            print("|".join(row))
    
    ```
3. **Get Player Input**
   ```python
   def get_player_input():
    position = int(input("Enter a position (1-9): ")) - 1
    row, col = divmod(position, 3)
    return row, col

   ```
4. **Making a Move**
   ```python
   def make_move(row, col, player):
    if board[row][col] == ' ':
        board[row][col] = player
        return True
    else:
        print("Invalid move. The cell is already occupied.")
        return False

   ```
5. **Checking for Winner**
   ```python
   def check_winner(player):
    # Check rows, columns, and diagonals for a line of the same symbol
    # Return True if there is a winner, False otherwise

   ```
6. **Main Game Loop to play Continuously**
   ```python
   def main():
    # Initialize the board
    # Display the board
    # Start the main game loop
        # Get player input
        # Make a move
        # Display the updated board
        # Check for a winner
    # Display the result (winner or draw)

   if __name__ == "__main__":
     main()

   ```

> [!Tip]
> You could do this as GUI project also and make a ai player to play against to enter into advanced dimensions of this project.
