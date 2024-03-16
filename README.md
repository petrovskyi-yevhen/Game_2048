# 2048 game

## [DEMO LINK](https://petrovskyi-yevhen.github.io/Game_2048/)

Some rules:
1) The game field is 4 x 4
2) Each cell can be empty or contain one of the numbers: 2, 4, 8 ... 2^n
3) The player can move cells with keyboard arrows
4) All numbers move in the selected direction until all empty cells are filled
   - 2 identical cells are combined into a doubled number
   - A combined cell cannot be combined twice in one move
5) The move is possible if at least one cell is changed after the move
6) After move 2 or 4 appears in a random empty cell. 4 probability is 10%
7) When a value of 2048 appears in any cell, a winning message is displayed.
8) The `game over` message is displayed if there are no more available moves.
9) The initial message when you start the game is hidden
10) The `Start` button changes to `Restart` after the first move.
11) `Restart` button reset the game to the initial state.
12) Each move increases the score. The number of points is increased by the sum of all the combined cells.
