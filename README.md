# Deep Q-Network (DQN) Agent for Gym Pendulum Environment

This repository contains a Python script that implements a Deep Q-Network (DQN) agent to interact with the Pendulum-v1 environment provided by OpenAI Gym. The agent is trained using reinforcement learning techniques to learn an optimal policy for controlling the pendulum.

---

## Requirements

- Python 3.x
- OpenAI Gym
- Keras
- Matplotlib
- Pygame

---

## Installation

1. Clone the repository to your local machine:

    ```bash
    https://github.com/UjjwalDeepXCIX/Pendulum_Simulation_using_Gym_Library.git
    ```

2. Install the required dependencies:

    ```bash
    pip install gym keras matplotlib pygame
    ```

---

## Usage

- Run the Python script to train the DQN agent and visualize its performance in the Pendulum environment:

    ```bash
    python dqn_pendulum.py
    ```

---

## Description

- `dqn_pendulum.py`: This script contains the implementation of the DQNAgent class, which defines the architecture and training process of the Deep Q-Network. It also interacts with the Pendulum environment to train and evaluate the agent's performance.

---

## Components

- **DQNAgent**: The DQNAgent class represents the agent that learns to control the pendulum using Deep Q-Learning. It consists of methods to create the neural network model, store and sample experiences for training, and perform actions based on the current state.

---

## Environment

The Pendulum-v1 environment is a physics-based simulation provided by OpenAI Gym. The agent's goal is to swing up the pendulum and maintain it in an upright position using torque control.

---

## Dependencies

- **OpenAI Gym**: Provides the reinforcement learning environments, including Pendulum-v1.
- **Keras**: Used to implement the neural network architecture for the DQN agent.
- **Matplotlib**: Utilized for visualizing the Pendulum environment.
- **Pygame**: Required for rendering the environment.

---

## Acknowledgments

This implementation is inspired by the work of researchers and practitioners in the field of reinforcement learning, particularly the Deep Q-Network algorithm proposed by Mnih et al. (2015).

---

## Disclaimer

This code is provided as-is, without any warranties or guarantees. Users are encouraged to review and modify the code to suit their specific needs and requirements.

