
This Java class, `MiniMaxID`, implements the MiniMax algorithm with a time-limited search for the Othello game. The algorithm is designed for an Othello player represented by the `PlayerID` class. The goal is to find the best move for the player within a given time limit.

### Features:

- **Algorithm:** The MiniMax algorithm is employed to search for the best move in the Othello game tree.
- **Time Limit:** The search is time-limited, ensuring that the algorithm returns a move within a specified time frame.
- **Heuristic Evaluation:** The class uses a heuristic function (`Heuristica`) to evaluate the game state and determine the desirability of a move.
- **Transposition Table:** The algorithm utilizes a transposition table (`BaseDades`) to store and retrieve previously computed heuristic values for board positions.
- **Zobrist Hashing:** The Zobrist hashing technique is applied to efficiently represent the board state and compute its hash value.
- **Alpha-Beta Pruning:** The algorithm uses alpha-beta pruning to enhance the efficiency of the search process.
