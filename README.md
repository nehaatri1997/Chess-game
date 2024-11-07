# Chess-game

This Python script implements a basic console-based chess game. The game allows two players to play against each other in a traditional chess setup, with standard rules governing piece movements and capturing.

# Features
Implements a chess game between two players.
Validates legal moves for all standard chess pieces.
Detects check and checkmate conditions.
Provides a command-line interface to play the game.
Displays the chessboard and updates it after each move.

# Prerequisites
Ensure you have Python 3 installed on your system. You can download Python here.

# Installation
Clone the repository or download chess_game.py directly.
python -m venv chess_env
source chess_env/bin/activate  # On Windows use `chess_env\Scripts\activate`
Install any dependencies (if required by the code):
pip install -r requirements.txt

# Usage
Run the script to start the chess game:
python chess_game.py

Follow the prompts in the command line to enter moves. Each move should be entered in standard chess notation (e.g., e2 e4 to move a piece from e2 to e4).

The game will continue until a checkmate, stalemate, or resignation.

# How to Play
Move Format: Enter moves in the format start_position end_position (e.g., b1 c3 to move a knight from b1 to c3).
Check and Checkmate: The game will notify players if they are in check or checkmate.
End Game: The game ends upon checkmate or if one player resigns.

# Code Structure
Board Initialization: Sets up the initial chessboard with all pieces in their respective starting positions.
Move Validation: Ensures each move is legal according to chess rules.
Check/Checkmate Detection: Identifies if a player is in check or checkmate.
Display Board: Prints the chessboard to the console, updating after each move.
