# Learning CartPole Dynamics with Neural Ordinary Differential Equations

This repository contains a small exploration of **Neural Ordinary Differential Equations (Neural ODEs)** for learning the nonlinear dynamics of the CartPole environment.

Rather than training an RL agent, the goal is to learn the system's dynamics directly from observed transitions and see how well a Neural ODE can reproduce the behavior of the simulator. As a reference, the notebook also compares the model against a standard MLP baseline.

Everything is contained in a single, fully executed Jupyter notebook, including the data generation, model implementation, experiments, visualizations, and a brief discussion of the results.

## Contents

- Data generation from the CartPole environment
- Neural ODE implementation in PyTorch
- MLP baseline
- One-step and multi-step prediction experiments
- Visual comparison of learned and true trajectories

This was built as a short research-oriented exploration while learning about Neural ODEs and data-driven modeling of nonlinear dynamical systems.
