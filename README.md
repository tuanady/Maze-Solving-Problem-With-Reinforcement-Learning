# Maze Solving Problem With Reinforcement Learning 
This project explores the implementation of Q-learning and Value Iteration algorithms in a 10x10 maze environment, designed to train an agent to navigate efficiently toward multiple objectives. By applying reinforcement learning, the agent learns an optimal path that reaches a sub-goal before continuing to a final goal, reinforcing both exploration and exploitation strategies.

This repository contains the following files:

- `q_learning.ipynb`: A Jupyter Notebook implementing the Q-learning algorithm in a maze environment. The agent interacts with the environment, learning to maximize cumulative rewards. The structured reward and penalty system guides the agent toward the sub-goal and final goal while minimizing unnecessary backtracking.

- `Pseudocode_q-learning.txt`: A text file with the pseudocode template for the Q-learning implementation. It outlines the algorithmic steps taken in the Python code, offering an overview of the Q-learning logic applied to the maze environment.

- `value_iteration.ipynb`: A Jupyter Notebook implementing the value iteration algorithm for solving the same maze. Here, the agent calculates the long-term expected reward for each state using the Bellman equation, and iteratively updates values until they converge, allowing the agent to derive an optimal policy.


## Running the Code

To run the code, open each Notebook in Jupyter and run all cells to train the agent within the maze environment. Each notebook outputs key metrics including performance statistics and visualizations.


## Evaluation and Comparison

Performance metrics, including success rate, average steps, and learning curves, are visualized for comparison. These insights demonstrate each algorithm’s effectiveness for navigation and decision-making tasks.


## Visualizations and Learning Curves

Learning curves and path visualizations are generated in each notebook to show the agent's progress and efficiency over time. These visualizations illustrate the agent's journey to optimal path-finding through reinforcement learning.
