# Pirate Intelligent Agent

A reinforcement learning project featuring a pirate agent navigating an 8x8 maze to find a treasure. The project focuses on Q-learning with experience replay, allowing the agent to learn optimal paths from experience.

---

## Technologies
- Python 3
- TensorFlow
- NumPy
- Matplotlib
- Reinforcement Learning (Deep Q-Learning)

---

## My Contribution

I implemented the Q-learning experience replay module, which stores episodes, trains the agent’s neural network, and allows the pirate to make decisions that maximize reward.

---

## Features

- Stores episodes (state, action, reward, next state, game status) for learning.
- Implements experience replay to train a neural network for pathfinding.
- Optimized agent navigation using Q-learning.
- Handles environment constraints such as blocked paths and revisited cells.
- Validates success using completion checks across all starting positions.

---

## Installation

1. Clone the repository
2. Install dependencies
3. Run the notebook or Python scripts to train and test the agent
