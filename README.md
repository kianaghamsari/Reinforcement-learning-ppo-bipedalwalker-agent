# PPO Agent for BipedalWalker-v3

This project implements a reinforcement learning agent using the Proximal Policy Optimization (PPO)
algorithm to solve the BipedalWalker-v3 continuous control environment.

> This project was originally developed as part of a university course.

## Overview
- Implemented PPO with separate policy and value networks
- Trained the agent on a continuous action space environment
- Evaluated performance using episodic rewards and visualizations

## Environment
- Gymnasium: BipedalWalker-v3
- Continuous state and action spaces

## Results
- Trained for 3000 episodes
- Best episode achieved a reward of ~240
- Performance improvement demonstrated through reward curves
- Best-performing episode saved as video

## Tech Stack
- Python
- PyTorch
- Gymnasium
- Jupyter Notebook

## Contents
- `Fifth_Assignment_RL.ipynb`: PPO implementation and training loop
- `Report_RL.pdf`: detailed technical report and analysis
- `results/`: reward plots and evaluation video
