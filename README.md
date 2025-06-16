# 🚀 Deep Q-Network on LunarLander-v2

This project implements a Deep Q-Network (DQN) using PyTorch to solve the **LunarLander-v2** environment from OpenAI Gymnasium.

## 🎯 Objective

Train an agent to land a lunar module safely between flags using a reinforcement learning algorithm.

---

## 🛠️ Technologies Used

- Python 3
- PyTorch
- OpenAI Gymnasium (`LunarLander-v2`)
- DQN (Deep Q-Network)
- Google Colab (for training)
- `imageio` (for recording video)

---

## 🧠 DQN Agent Structure

- **Neural Network**: 3-layer feedforward network
- **Replay Buffer**: Stores past experiences to break temporal correlations
- **Epsilon-Greedy Policy**: For exploration vs exploitation
- **Soft Update**: Updates target network with interpolation

---

## 📊 Results

The agent solves the environment when the average reward over 100 episodes exceeds 200.

| Metric           | Value       |
|------------------|-------------|
| Episodes         | ~600–1200   |
| Avg Score Goal   | ≥ 200       |
| Replay Buffer    | 100,000     |

---

