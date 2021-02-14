# NeuralNetworkChess
An attempt to make a neural network play chess.

## Steps
- Download dependencies.
- Download some chess games.
- Convert chess games to train data for the neural network.
- Train the model and save it.
- Play with it.

## Problems
The model probably doesn't learn how to play chess, rather memorizing other chess grandmaster's positions and their responses, therefore it's just memorizing and hoping to give the best response to you. This can be seen when it outputs an illegal move, a move that you can't do in terms of chess, so the algorithm just chooses a legal move with the highest probability model gave.
But it was a fun little project, so don't expect much. 
