# Renewable Energy Grid Optimization Using Reinforcement Learning

This project applies reinforcement learning (RL) to optimize the operation of a renewable energy grid by balancing energy demand, renewable supply (solar and wind), and battery storage. It demonstrates how RL agents can improve grid efficiency and resilience.

## Project Overview

The workflow includes:
- Simulating a renewable energy grid environment with dynamic demand and renewable energy generation.
- Defining actions such as storing energy, using it to meet demand, or selling excess energy back to the grid.
- Implementing a Deep Q-Network (DQN) agent to learn optimal strategies.
- Training the agent over multiple episodes to maximize rewards based on grid performance.

## Files Generated

- `Renewable_Grid_Optimization_Results.xlsx` — Excel file containing:
  - **Episode** number
  - **Total Reward** per episode
  - **Final Battery Level** at the end of each episode

## How to Use

1. **Prepare the Environment**:
   - Install the required Python libraries:
```bash
pip install numpy pandas gym tensorflow openpyxl
```

2. **Run the Script**:
   - Load the environment and train the DQN agent.
   - Monitor episode rewards and battery performance.

3. **Review the Results**:
   - Open `Renewable_Grid_Optimization_Results.xlsx`.
   - Analyze training performance trends.

## Key Features

- **Custom Gym Environment**: Models realistic grid behavior with solar, wind, demand, and storage dynamics.
- **Reinforcement Learning**: Uses DQN to learn optimal energy management strategies.
- **Performance Metrics**: Tracks total rewards and battery levels across episodes.

## Author

Ayebawanaemi Geraldine Winston
