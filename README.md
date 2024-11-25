# Tic-Tac-Toe
# Description
This is a simple Tic Tac Toe game implemented in Python using the Tkinter library. The game features a graphical user interface (GUI) where two players can take turns playing. The game supports:

- Displaying the game board with a 3x3 grid.
- Switching turns between Player X and Player O.
- Detecting and announcing the winner or a draw.
- Resetting the game for a new round.
## Features
- Interactive GUI: Players click on the grid to make their moves.
- Win Detection: Checks rows, columns, and diagonals for a win.
- Draw Detection: Declares a draw when all cells are filled and no winner is found.
- Game Reset: Automatically resets the board after a win or a draw.
## Prerequisites
- Python 3.x installed on your system.
- Tkinter (comes pre-installed with Python).
## How to Run
- Download the code and save it as tic_tac_toe.py.
- Open a terminal or command prompt and navigate to the directory containing the file.
- Run the script using:
```
python tic_tac_toe.py
```
## How to Play
- The game starts with Player X.
- Click on a cell in the 3x3 grid to place your symbol (X or O).
- The game automatically alternates turns between Player X and Player O.
- A pop-up will appear announcing the winner or declaring a draw.
- The board resets automatically after a win or draw, and the game can be played again.
## Game Logic
- Win Conditions:
      - Three identical symbols in a row.
      - Three identical symbols in a column.
       - Three identical symbols diagonally.
- Draw Condition:
     - All cells are filled, and no winner is detected.


## Code Highlights
- Canvas for GUI: The game board is drawn using the Canvas widget.
- Event Handling: Mouse clicks are captured and processed to update the game state.
- Winner Detection: Rows, columns, and diagonals are checked after each move.
- Reset Functionality: The board resets automatically after a game ends.
## Future Improvements
- Add a score tracker for multiple rounds.
- Include AI for single-player mode.
- Customize the appearance with colors and animations.
