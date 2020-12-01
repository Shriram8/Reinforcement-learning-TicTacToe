# Tic tac toe  using Q learning.

Reinforcement Learning Objective
The objective for any reinforcement learning problem is to find the sequence of actions that maximizes (or minimizes) the sum of reinforcements along the sequence. This is reduced to the objective of acquiring the Q function the predicts the expected sum of future reinforcements, because the correct Q function determines the optimal next action.

So, the RL objective is to make this approximation as accurate as possible:
This is usually formulated as the least squares objective
What is that expectation taken over?

Sources of randomness:

1.action selection
2.state transitions
3.reinforcement received

The objective of Tic-Tac-Toe is to be the first to place their marks (either cross or naughts) in a horizontal, vertical, or diagonal arrangement. Now, let us define the game in terms of RL keywords mentioned earlier:
Agents involve 2 Tic-Tac-Toe players who attempt to outwit each other by taking a turn to place their mark,
Reward refers to an arbitrary value earned by the winning agent,
Actions dictate that each agent is allowed to place their corresponding mark only in an empty box,
The state is the configuration of the tic-tac-toe board after each turn until the game ends in either a win or a draw.

In this notes i have made observations based on winning strategy of X player and O player in tic-tac-Toe game by changing the configurations of Network and parameters.
