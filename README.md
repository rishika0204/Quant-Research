
# Quant Research - Reinforcement Learning Algorithms

This repository contains implementations of various Reinforcement Learning (RL) algorithms, tailored for experimentation in quantitative research and algorithmic trading environments.

## 📂 Repository Structure

- **`dqn.ipynb`** - Deep Q-Network (DQN) implementation. Combines Q-learning with deep neural networks to handle high-dimensional state spaces, enabling decision-making in complex financial environments.
- **`mc_control.ipynb`** - Monte Carlo Control implementation for on-policy and off-policy methods. Uses episodic sampling to estimate value functions for trading strategies.
- **`q_learning.ipynb`** - Q-Learning algorithm implementation. A model-free off-policy RL method for optimal policy discovery in discrete state-action spaces.
- **`reinforce.ipynb`** - REINFORCE algorithm (Monte Carlo Policy Gradient). Learns stochastic policies directly by maximizing expected returns, useful for continuous decision spaces in trading.
- **`sarsa.ipynb`** - SARSA (State–Action–Reward–State–Action) algorithm implementation. An on-policy TD control method for stable strategy learning under uncertainty.

## 🚀 Getting Started

### 1️⃣ Clone the repository
```bash
git clone https://github.com/your-username/quant-research-rl.git
cd quant-research-rl
```

### 2️⃣ Install dependencies
It's recommended to use a virtual environment:
```bash
python -m venv venv
source venv/bin/activate  # On Windows use: venv\Scripts\activate
pip install -r requirements.txt
```

### 3️⃣ Run notebooks
You can run each Jupyter notebook individually:
```bash
jupyter notebook dqn.ipynb
```

## 📈 Applications in Quant Research
These algorithms can be adapted for:
- **Trading strategy optimization** – Learning profitable strategies in simulated or historical market environments.
- **Risk management** – Dynamically adjusting exposure based on market states.
- **Portfolio allocation** – Using RL to rebalance portfolios in changing market conditions.
- **Execution algorithms** – Optimizing trade execution to minimize costs and slippage.

## 📚 References
- Sutton, R. S., & Barto, A. G. (2018). *Reinforcement Learning: An Introduction*.
- Mnih, V. et al. (2015). *Human-level control through deep reinforcement learning*. Nature.
- Silver, D. et al. *Deterministic Policy Gradient Algorithms*.
