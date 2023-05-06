# Tic Tac Toe

This is a Tic Tac Toe game developed using Python programming language and implemented with the Minimax algorithm. The Minimax algorithm is used to create an unbeatable computer opponent for the game.

# Installation
1. Download or clone the repository.

If you have Anaconda installed in your system, then follow the steps below:

2. Launch Jupyter Notebook in your system.
3. Open the tic_tac_toe.ipynb file in the Jupyter Notebook.
4. Run all the cells.
5. The last cell has the main() function where you can play the game.

If you do not have Anaconda installed in your system, then follow the steps below:

2. Open Google Colab.
3. Open the tic_tac_toe.ipynb file in the Colab.
4. Run all the cells.
5. The last cell has the main() function where you can play the game.

# Game Rules
1. The game is played on a 3x3 grid.
2. The first player is X and the second player is O.
3. Players take turns placing their mark (X or O) on an empty square on the grid.
4. The first player to get 3 of their marks in a row (horizontally, vertically, or diagonally) wins the game.
5. If all squares are filled and no player has won, the game is a draw.

# Minimax Algorithm
The Minimax algorithm is a decision-making algorithm used in game theory to find the optimal move for a player. In this game, the algorithm is used to create an unbeatable computer opponent. The algorithm works by recursively exploring all possible moves from the current game state and assigning a score to each state. The score is based on the assumption that both players will play optimally. The algorithm then chooses the move that leads to the highest score for the current player and the lowest score for the opponent.

<p align="center">
    <img width="500" src="https://user-images.githubusercontent.com/71036685/236631557-2042f780-aa75-4db3-8092-c66559248a78.png" alt="Minimax Algorithm">
</p>

# Representation
<p align="center">
    <img width="800" src="https://i.stack.imgur.com/ZXEdz.png" alt="Tic Tac Toe Board using Minimax Algorithm">
</p>
