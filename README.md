# Reinforcement Learning Course

This repository contains the assignments for my Reinforcement Learning course.  The assignments cover various aspects of RL, from basic discrete state and action problems to more advanced topics like regression and implementing common RL algorithms.

## Folder Structure
```
├── Controllers/
│   └── Assignment 5/
├── Discrete state & action/
│   ├── Assignment 1/
│   ├── Assignment 2/
│   └── Assignment 3/
├── regression/
│   └── Assignment 4/
└── RL Algorithms/
    └── Assignment 6/
```
## Assignments

*   **Assignment 1: Grid World Value Functions:** This assignment involves creating a model of a given grid world and calculating the state and action value functions.  This provides a foundation for understanding how to evaluate different states and actions within a simple environment.

*   **Assignment 2: Grid World Optimal Policy:** Building upon Assignment 1, this assignment focuses on calculating the optimal policy for reaching a desired location within the grid world.  This demonstrates how to determine the best sequence of actions to achieve a specific goal.

*   **Assignment 3: Cartpole Control with Q-Learning:**  Using the Gymnasium library, this assignment implements Q-learning to control the classic cartpole problem.  The key steps include constructing the Q-table and finding the optimal policy to balance the pole.

*   **Assignment 4: Linear Regression:** This assignment explores regression techniques by performing linear regression on a given dataset and comparing the results with those obtained using a neural network.

*   **Assignment 5: MPC Controller with Casadi:** This assignment utilizes the Casadi solver to construct a Model Predictive Control (MPC) controller.  MPC is a powerful technique for optimizing control actions over a finite horizon.

*   **Assignment 6: DQN and DDPG for Lunar Lander:**  Using the Gymnasium library, this assignment implements and trains Deep Q-Networks (DQN) and Deep Deterministic Policy Gradients (DDPG) to control the Lunar Lander environment.  The performance of the two algorithms is then compared in terms of episode length and rewards.

## Libraries Needed for Each Assignment  

Each assignment requires specific libraries to run. Below is a list of dependencies categorized by assignment:

- **Assignment 1 & 2: Grid World (Value Functions & Optimal Policy)**
  - `numpy`
  - `matplotlib`

- **Assignment 3: Cartpole Control with Q-Learning**
  - `gymnasium`
  - `numpy`
  - `matplotlib`

- **Assignment 4: Linear Regression**
  - `numpy`
  - `matplotlib`
  - `scikit-learn`
  - `tensorflow` (for neural network comparison)

- **Assignment 5: MPC Controller with Casadi**
  - `casadi`
  - `numpy`
  - `matplotlib`

- **Assignment 6: DQN and DDPG for Lunar Lander**
  - `gymnasium`
  - `numpy`
  - `torch`
  - `matplotlib`

You can install all required dependencies using:  

```bash
pip install gymnasium numpy matplotlib scikit-learn torch casadi


