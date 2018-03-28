# Game Walkthrough:
1. This is a 9x9 tictactoe
2. After opening the app you will see 2 buttons in home page ie Play and Instructions.
3. If you are playing for the first time, we recommend you to go through the instructions.
4. Enter the names of the 2 players and then start playing.
5. Your next allowed move in the game is highlighted by the color given.
6. Keep track of your won blocks in the score board below the grid.
7. You may undo your move or reset the game anytime.
8. You need to win atmost 5 blocks to win the whole game.
9. After a move, undo will work only once.

# Known Issues:
1. Undo command does not decrement the win-counter after winning of a block.
2. If game enters deadlock(due to the rules of the game) the whole grid is enabled(Its not an actual issue).
3. There is some mismatch in the color of the a block, it occurs very seldom.

# Concepts Used:
1. Multiple Activities
2. Interactive Buttons
3. Constraint Layout
4. Realtime Color Changing Layout
5. Screen Constraints
6. Supports Multiple Screen Resolutions.

# Future Changes:
1. Add a timer to make it more challenging.
2. A database will be maintained to keep a record of the users and their best scores.
3. Make the game single player(ie enable bot players).
4. Players can play the game over bluetooth/wifi(offline) remotely.
