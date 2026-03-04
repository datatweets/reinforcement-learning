# reinforcement-learning

A comprehensive hands-on guide to Reinforcement Learning, covering core concepts, mathematical foundations, key algorithms, and practical deep RL techniques.

---

## About This Course

This repository contains a structured, notebook-based course designed for **AI/ML engineers and learners** who want to go from zero to confident in Reinforcement Learning. Every part balances theory with working Python code, real-world analogies, and visual intuition — no prior RL experience required.

**Instructor**: Mehdi Lotfinejad  
**Format**: Jupyter Notebooks  
**Level**: Beginner to Intermediate

---

## Course Outline

| # | Notebook | Topics Covered | Duration |
|---|----------|----------------|----------|
| 1 | [Part 01 — Introduction to RL](Part_01_Introduction_to_Reinforcement_Learning.ipynb) | What is RL, the agent-environment loop, 5 building blocks (Agent, Environment, State, Action, Reward), RL vs supervised/unsupervised learning, real-world applications, first RL agent from scratch | 1.5 hrs |
| 2 | [Part 02 — Mathematical Foundations & MDPs](Part_02_Mathematical_Foundations_MDPs_Bellman.ipynb) | Markov Decision Processes, state/action/reward spaces, discount factor, Bellman equations, value functions, policy vs value | ~2 hrs |
| 3 | [Part 03 — Key RL Algorithms](Part_03_Key_RL_Algorithms_DP_MC_QLearning_SARSA.ipynb) | Dynamic Programming, Monte Carlo methods, Temporal Difference learning, Q-Learning, SARSA, tabular methods | ~2 hrs |
| 4 | [Part 04 — Deep RL](Part_04_Deep_RL_DQN_PolicyGradient_PPO_TRPO.ipynb) | Deep Q-Networks (DQN), Policy Gradient methods, PPO, TRPO, actor-critic architectures | ~2.5 hrs |
| 5 | [Part 05 — Exploration vs Exploitation](Part_05_Exploration_vs_Exploitation.ipynb) | The explore/exploit dilemma, epsilon-greedy, UCB, Thompson Sampling, curiosity-driven exploration | ~1.5 hrs |
| 6 | [Part 06 — Practical Challenges & Solutions](Part_06_Practical_Challenges_and_Solutions_in_RL.ipynb) | Common RL failure modes, reward hacking, sparse rewards, sample efficiency, training instability, hyperparameter tuning, the RL development loop | 2.5 hrs |

---

## Prerequisites

You don't need to know RL going in, but the following helps:

- Python basics (functions, loops, classes)
- Some familiarity with NumPy
- High-school level math (probability, basic calculus)

---

## Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/datatweets/reinforcement-learning.git
cd reinforcement-learning
```

### 2. Create a virtual environment

```bash
python -m venv .venv
source .venv/bin/activate        # macOS / Linux
# .venv\Scripts\activate         # Windows
```

### 3. Install dependencies

```bash
pip install jupyter numpy matplotlib gymnasium torch stable-baselines3
```

### 4. Launch Jupyter

```bash
jupyter notebook
```

Open the notebooks in order, starting with `Part_01`.

---

## How to Use This Repository

- Work through the notebooks **in order** — each part builds on the previous one.
- Every notebook includes:
  - Clear learning objectives at the top
  - Real-world analogies before any math
  - Runnable Python code cells
  - Visual diagrams and training plots
- If you get stuck on a concept, re-read the analogy section before the code.

---

## Repository Structure

```
reinforcement-learning/
├── Part_01_Introduction_to_Reinforcement_Learning.ipynb
├── Part_02_Mathematical_Foundations_MDPs_Bellman.ipynb
├── Part_03_Key_RL_Algorithms_DP_MC_QLearning_SARSA.ipynb
├── Part_04_Deep_RL_DQN_PolicyGradient_PPO_TRPO.ipynb
├── Part_05_Exploration_vs_Exploitation.ipynb
├── Part_06_Practical_Challenges_and_Solutions_in_RL.ipynb
├── *.png                   # Diagrams and training visualizations
├── .gitignore
└── README.md
```

---

## Key Concepts at a Glance

| Concept | One-line Summary |
|---------|-----------------|
| **Agent** | The learner — takes actions in the environment |
| **Environment** | The world the agent interacts with |
| **State** | A snapshot of the current situation |
| **Action** | A choice the agent can make |
| **Reward** | Feedback signal — tells the agent how well it's doing |
| **Policy** | The agent's strategy: given a state, what action to take |
| **Value Function** | How good is it to be in a given state? |
| **Q-Function** | How good is a specific action in a specific state? |
| **Bellman Equation** | Recursive relationship that ties current and future value |

---

## License

This course material is provided for educational purposes. Feel free to use it for personal learning and share it with others who want to learn RL.

---

## Author

**Mehdi Lotfinejad**  
AI/ML Engineer & Educator  
GitHub: [@datatweets](https://github.com/datatweets)
# reinforcement-learning
