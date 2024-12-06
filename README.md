# Lunar Lander with Deep Q-Learning (DQN)

This repository contains the implementation of **Deep Q-Learning (DQN)** to solve the Lunar Lander environment from OpenAI Gym. The goal is to train an agent to land a spacecraft safely between flags using reinforcement learning.

---

## Features

- **Environment**: LunarLander-v2 from OpenAI Gym.
- **Deep Q-Learning (DQN)**: Uses a neural network to approximate Q-values.
- **Replay Buffer**: Stabilizes learning by storing and sampling past experiences.
- **Epsilon-Greedy Policy**: Balances exploration and exploitation.
- **Soft Updates**: Improves stability of training by periodically updating the target network.

---

## Requirements

- Python 3.7+
- Libraries:
  - `gym`
  - `torch`
  - `numpy`
  - `matplotlib`
