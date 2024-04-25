# Reinforcement Learning on Highway-env

This project focuses on implementing and experimenting with Reinforcement Learning (RL) methods on the Highway-env collection of environments. The project is divided into three main parts, each focusing on a different aspect of RL.

## Table of Contents
1. [Preliminary](#preliminary)
2. [Highway Fast Environment](#highway-fast-environment)
3. [Continuous Actions](#continuous-actions)
4. [Reference Implementations: Stable Baselines](#reference-implementations-stable-baselines)

## Preliminary <a name="preliminary"></a>
Before starting the project, it is essential to understand the environment's documentation and configuration. The Highway-env allows for multiple configurations of observations and actions, leading to significant changes in the environment. The actions can be either discrete or continuous, and the set of available actions may change depending on the state.

## Highway Fast Environment <a name="highway-fast-environment"></a>
In the Highway Fast Environment task, the goal is to solve the `highway-fast` environment using a Deep Q-Network (DQN) implemented from scratch. The code for this task is located in the Jupyter notebook `highway_fast_dqn.ipynb`.
Weights are already ready to test the model with files `highway_fast_dqn_1000.pth` (1000 episodes) and `highway_fast_dqn_5000.pth` (5000 episodes)

## Continuous Actions <a name="continuous-actions"></a>
For the Highway Parking Environment task, we tested two approches implemented in `parking_ppo.ipynb` and `parking_ddpg_with_her.ipynb`, located in the folder `parking_env`.

## Reference Implementations: Stable Baselines <a name="reference-implementations-stable-baselines"></a>
For the Highway Racetrack Environement task, we studied the implementation of SAC algorithm with two different reward configuration. The notebooks are located in `racetrack_env`.



