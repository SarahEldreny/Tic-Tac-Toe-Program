# ***Tic-Tac-Toe-Program***

Here's an outline that combines your steps in providing a detailed step-by-step decomposition of the game logic for building a Tic Tac Toe game in Python into a coherent structure:

1. Design the game board as a 3x3 list of lists. Initialize each element as an empty string.
1. Create a function `print_board(board)` to print the game board to the console using loops to iterate through rows and columns.
1. Create a function `handle_move(board, player_symbol)` to handle player moves. Prompt the player for their move using `input()` and update the game board accordingly.
1. Create a function `check_win(board, player_symbol)` to check if the current player has won. Check all possible winning combinations in rows, columns, and diagonals.
1. Create a function `check_tie(board)` to check if the game has resulted in a tie by verifying if all squares on the board are filled.
1. Create a main game loop that alternates between the two players. Inside the loop:
   - Print the current state of the game board using `print_board(board)`.
   - Prompt the current player for their move using `handle_move(board, player_symbol)`.
   - Check if the game has been won using `check_win(board, player_symbol)` and end the loop if a player has won.
   - Check if the game has resulted in a tie using `check_tie(board)` and end the loop if it's a tie.
   - Switch the current player's symbol for the next iteration.
1. After the main game loop ends, print the appropriate message indicating the winner or a tie.
1. Test the game by playing it and verifying that it functions correctly. Debug any issues that arise.

Following this decomposition, you should be able to implement the Tic Tac Toe game in Python step by step. 
