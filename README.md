# RL Course - Spring 2024 | Sharif University of Technology

This repository contains the homework assignments and projects for the graduate-level Reinforcement Learning (RL) course at Sharif University of Technology, Spring 2024. The course covers a wide range of topics in RL, from foundational methods to advanced algorithms.

## Table of Contents
1. [Poster Session: Combinatorial Causal Bandits](#poster-session-combinatorial-causal-bandits)
2. [Homework Details](#homework-details)

---

---

## Poster Session: Combinatorial Causal Bandits

In addition to the course assignments, a poster session was conducted where I presented my work on **Combinatorial Causal Bandits**. This topic intersects reinforcement learning with causal inference, focusing on decision-making in environments where actions influence outcomes based on causal relationships, and optimal actions are selected from combinatorial options.

### Overview of Combinatorial Causal Bandits

- **Objective:** To address problems where an agent must make decisions that not only maximize rewards but also consider causal structures in complex, combinatorial action spaces.
- **Key Challenges:**
  - **Causal Inference in Bandit Settings:** Understanding and leveraging causal relationships to improve decision-making.
  - **Combinatorial Action Spaces:** Dealing with a large number of possible action combinations, which makes exploration and exploitation more challenging.
- **Methods:** The approach combines causal inference techniques with multi-armed bandit algorithms to prioritize actions based on inferred causal impacts. This is particularly relevant in scenarios where actions affect the environment in a combinatorial manner.
- **Applications:** Such frameworks have applications in personalized recommendations, medical treatments, and any domain where understanding the causal impact of combined actions is crucial.

### Poster Highlights

The poster provided an overview of:
- Theoretical foundations of causal bandits and their adaptation to combinatorial settings.
- Algorithmic approaches to efficiently explore and exploit in causal environments.
- Simulation results demonstrating the effectiveness of this approach in synthetic environments.

**Files:** `Combinatorial Causal Bandits.pdf`

---


## Homework Details

1. [Homework 1: Theoretical Foundations](#homework-1-theoretical-foundations)
2. [Homework 2: Monte Carlo and Temporal Difference Learning, Deep Q-Networks (DQN)](#homework-2-monte-carlo-and-temporal-difference-learning-deep-q-networks-dqn)
3. [Homework 3: Off-Policy Methods - REINFORCE and PPO](#homework-3-off-policy-methods---reinforce-and-ppo)
4. [Homework 4: Offline Reinforcement Learning](#homework-4-offline-reinforcement-learning)

### Homework 1: Theoretical Foundations

- **Objective:** This assignment provides a strong theoretical foundation for reinforcement learning, focusing on essential concepts in related fields such as information theory and optimization.
- **Topics Covered:**
  - Information theory fundamentals
  - Optimization techniques
  - Variational calculus
  - Stochastic processes
  - Variational inference
- **Files:** 
  - `RL_HW1_Theory.pdf` - Theoretical assignment covering foundational topics crucial for understanding advanced RL concepts.

### Homework 2: Monte Carlo and Temporal Difference Learning, Deep Q-Networks (DQN)

- **Objective:** This assignment explores Monte Carlo methods, temporal difference (TD) learning, and introduces Deep Q-Networks (DQN).
- **Topics Covered:**
  - Monte Carlo (MC) prediction and control
  - Temporal Difference (TD) methods, including TD(0) and Q-learning
  - Introduction to Deep Q-Networks (DQN) and using neural networks for Q-value approximation
- **Files:** 
  - `RL_PHW2_MC_TD.ipynb` - Practical notebook covering Monte Carlo and Temporal Difference learning methods.
  - `RL_PHW2_DQN.ipynb` - Practical notebook introducing and implementing DQN.
  - `RL_HW2_Theory.pdf` - Theoretical assignment with questions on MC, TD, and DQN concepts.

### Homework 3: Off-Policy Methods - REINFORCE and PPO

- **Objective:** This homework focuses on off-policy methods, specifically REINFORCE and Proximal Policy Optimization (PPO), two popular algorithms in RL for policy optimization.
- **Topics Covered:**
  - REINFORCE algorithm for policy-gradient based learning
  - Introduction and implementation of Proximal Policy Optimization (PPO), a widely-used method for stability in policy updates
  - Comparison of REINFORCE and PPO in terms of stability and sample efficiency
- **Files:** 
  - `RL_HW3_On_Policy.ipynb` - Practical notebook with implementations of REINFORCE and PPO.
  - `RL_HW3_Theory.pdf` - Theoretical assignment on policy-gradient methods and PPO.

### Homework 4: Offline Reinforcement Learning

- **Objective:** Delve into Offline RL, where learning is based on fixed datasets without additional environment interactions, a common scenario in real-world applications where online exploration is limited.
- **Topics Covered:**
  - Offline RL fundamentals and challenges
  - Techniques for training policies on pre-collected datasets
  - Evaluation of policy performance in offline settings
- **Files:**
  - `RL_HW4_Practical.ipynb` - Practical notebooks on offline RL methods and analysis.
  - `RL_HW4_Theory.pdf` - Theoretical assignment discussing key concepts and issues in Offline RL.

---

This repository serves as a comprehensive resource for understanding and implementing key RL concepts, with both practical exercises and theoretical assignments to facilitate learning.
