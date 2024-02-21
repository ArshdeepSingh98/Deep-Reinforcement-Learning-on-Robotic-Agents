This project is associated with Arizona State University, released under CSE 574: Planning/Learning Methods AI course. I have provided overview of this individual project. For access to the complete source code, please contact me at my [email](mailto:asroideva@gmail.com) address.

# Deep Reinforcement Learning on Robotic Agents
Duration: Sept 2023 - Oct 2023

---

## Overview

The project focuses on applying Reinforcement Learning (RL) algorithms to train agents in two distinct environments provided by the Gym library: Cartpole and Humanoid. The Cartpole agent learns to balance itself, while the Humanoid agent learns to walk. The team utilized the Stable Baselines3 library, Gymnasium, and MuJoCo for efficient implementation and realistic physics simulation.

## Methodology

For the Cartpole environment, the team employed Deep Q-Network (DQN) and Proximal Policy Optimization (PPO) algorithms, discovering that PPO performed the best. In the Humanoid environment, five algorithms were explored: PPO, Soft Actor-Critic (SAC), Deep Deterministic Policy Gradient (DDPG), Twin Delayed Deep Deterministic Policy Gradient (TD3), and Advantage Actor-Critic (A2C). A2C was identified as the most effective algorithm for teaching the Humanoid agent to walk.

The project highlights the importance of Gymnasium, a versatile Python library offering pre-built environments for RL tasks, MuJoCo for realistic physics simulation, and Stable Baselines3 for its user-friendly interface. The team trained each RL algorithm for 1 million time steps and used MlpPolicy for each algorithm from Stable Baselines3.

## Skills

-   Reinforcement Learning
-   Deep Learning
-   Python Programming
-   Simulated Environments
-   Physics Simulation
-   Data Analysis and Visualization
-   Problem-solving and Optimization
-   Algorithm Selection and Evaluation

## Demo Videos and Graphs

### Cartpole

![Cartpole Demo](/assets/videos/Cartpole-PPO.gif)
<br>
Demonstration of balancing of Cartpole using PPO RL Algorithm

![Cartpole Results](/assets/images/Cartpole-Results.png)
<br>
Showcasing training performance comparison of two algorithms (PPO and DQN) by using Average Reward vs Timesteps graph in Cartpole Gym environment.

### Humanoid

![Humanoid Demo](/assets/videos/Humanoid-SAC.gif)
<br>
Demonstration of an Humanoid Agent walking using SAC algorithm

![Humanoid Results](/assets/images/Humanoid-Results.png)
<br>
Showcasing training performance comparison of algorithms (SAC, A2C, DDPG, TD3, PPO) by using Average Reward vs Timesteps graph in Humanoid Gym environment.


