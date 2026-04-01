# Tic-Tac-Toe-AI-using-Minimax-Alpha-Beta-Pruning

This project implements a graphical Tic Tac Toe game in Python where a human player competes against an intelligent AI opponent. The AI is designed using two classic game theory algorithms: the Minimax algorithm and its optimized version, Alpha-Beta pruning. The game is built with the Pygame library, providing an interactive interface and real-time visual feedback.

The objective of this project is to demonstrate how decision-making algorithms can be applied to simple games to create an optimal and competitive AI. The Minimax algorithm explores all possible game states recursively and selects the move that maximizes the AI’s chances of winning while minimizing the opponent’s chances. Although effective, Minimax can be computationally expensive. To address this, Alpha-Beta pruning is implemented as an optimization technique that reduces the number of nodes evaluated in the search tree, significantly improving performance without affecting the outcome.

The game interface includes a 3x3 grid, turn-based gameplay, and automatic detection of wins and draws. Visual elements such as symbols and winning lines enhance the user experience. The player interacts with the game through mouse clicks, while the AI responds instantly with the best possible move.

This project highlights key concepts in artificial intelligence, including adversarial search, recursive problem solving, and performance optimization. It serves as a practical example of how theoretical algorithms can be translated into interactive applications.

Technologies used in this project include Python for implementation, Pygame for the graphical interface, and standard libraries for handling logic and mathematical computations.
