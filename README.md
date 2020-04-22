# Multiplayer-Tic-Tac-Toe
We all have heard and played this game known as Tic Tac Toe.
For those who never heard abt this game, I provided a link to a video which will give you a brief of this game.
link: https://www.youtube.com/watch?v=5SdW0_wTX5c
## Code Description
This is a code for multiplayer Tic Tac Toe Game in Python. No predefined library is used.
If you are facing any problem in understading functions, for that I have provided a description about all the functions that I used in this code.
## Display_board():
  It will display the board of the game with current state
## valid(pos):
  This is function which takes one integer argument known as position, which will actually check the validity of the move taken by the player.
## handle_turn():
  This function will handle the turn of X player or O player, and allow them to take their move.
## flip_player():
  This will actually take the pass from the current player and gives it to the another player, so that another player can take his turn.
## check_row():
  This will check each row of the matrix, if any player is won or not.
## check_col():
  This will check each column of the matrix, if any player is won or not.
## check_diagonal():
  This will check each diagonal of the matrix, if any player is won or not.
## check_tie():
  This will check, if the game is tie or not.
## who_won():
  This function is just a trigger function of all four above defined funcitons (check_row(), check_col(), check_diagonal(), check_tie())
## play_game():
  This is the main driver function.
