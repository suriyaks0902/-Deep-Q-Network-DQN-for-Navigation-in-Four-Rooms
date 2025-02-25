# Deep Q-Network (DQN) for Navigation in Four Rooms

### Four Room Environment
![Four Rooms Environment](four_rooms.gif)

### Loss Plot
![Loss Plot](loss_plot.png)

### Returns Plot
![Returns Plot](returns_plot.png)


## Project Overview
This project implements a **Deep Q-Network (DQN)** to train an agent for **autonomous navigation** in the **Four Rooms environment**. The agent learns an optimal policy using **reinforcement learning** by interacting with the environment and updating its Q-values. The project demonstrates **decision-making AI**, **trajectory planning**, and **reward-based learning**.

## Key Features
- **Deep Q-Network (DQN) Implementation**: Uses a **feedforward neural network** to approximate the Q-function.
- **Replay Buffer & Target Network Updates**: Enhances training stability and prevents catastrophic forgetting.
- **ε-Greedy Exploration & Batch Q-Learning**: Balances exploration and exploitation to optimize trajectory learning.
- **Custom Reward Function**: Encourages efficient navigation by penalizing non-optimal paths.
- **Performance Analysis**: Includes **loss curve** and **discounted return plots** to visualize training progress.

## Environment - Four Rooms
The Four Rooms environment consists of a **grid-based navigation task**:
- The agent starts at a predefined location.
- The goal is to navigate to a target location while avoiding walls.
- **Reward Structure**:
  - `0` for reaching the goal (episode ends).
  - `-1` for every other time step to encourage efficient paths.

## Training Results
- The **loss function plot** shows initial instability followed by convergence, indicating successful learning.
- The **discounted return plot** demonstrates increasing rewards as the agent optimizes its navigation strategy.

## Results & Performance
- **Efficient Learning**: DQN learns an optimal policy within `~100,000` steps.
- **Stable Convergence**: Loss decreases over training, and rewards increase significantly.
- **Trajectory Optimization**: The agent learns to navigate efficiently with minimal steps.

