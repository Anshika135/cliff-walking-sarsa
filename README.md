# Cliff Walking Problem using SARSA (Reinforcement Learning)

## 📌 Project Overview
This project implements the **SARSA (State-Action-Reward-State-Action)** algorithm to solve the classic **Cliff Walking problem** in Reinforcement Learning.

The objective is to train an agent to learn the optimal path from the start state to the goal while avoiding the cliff region, which results in large negative rewards.

---

## 🧠 Reinforcement Learning Concept

- **Environment:** Grid World (Cliff Walking)
- **Agent:** Learns optimal policy through interaction
- **Goal:** Reach destination with maximum cumulative reward

---

## ⚙️ Algorithm Used

### SARSA (On-Policy Learning)

SARSA updates the action-value function based on the current action and the next action chosen by the policy.

**Update Rule:**

Q(s, a) ← Q(s, a) + α [r + γ Q(s', a') − Q(s, a)]

Where:
- s = current state  
- a = current action  
- r = reward  
- s' = next state  
- a' = next action  
- α = learning rate  
- γ = discount factor  

---

## 🗺️ Environment Description

- Grid-based environment
- Start state → Goal state
- Cliff region gives high negative reward
- Agent must learn safest optimal path

---

## 🔄 Project Workflow

1. Initialize Q-table
2. Choose action using ε-greedy policy
3. Take action and observe reward
4. Update Q-values using SARSA update rule
5. Repeat for multiple episodes
6. Evaluate learned policy

---

## 📊 Results

- Agent successfully learns to avoid the cliff
- Converges to a safe and optimal path
- Demonstrates behavior differences compared to Q-learning

---


---

## 📈 Key Learnings

- Understanding of on-policy vs off-policy learning
- Implementation of SARSA algorithm
- Exploration vs exploitation trade-off
- Reinforcement learning environment interaction

---

## 🚀 Future Improvements

- Compare with Q-Learning
- Implement Deep Q-Network (DQN)
- Add visualization of agent movement
- Extend to larger environments

---

## 🤝 Contributing

Contributions are welcome! Feel free to fork and improve the project.

---

