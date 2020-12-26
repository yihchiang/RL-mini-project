# Implement Reinforcement Learning on BipedalWalker-v3
This is a simple example of how to implement reinforcement learning on BipedalWalker-v3 using stable-baselines.

You can see the complete tutorial for stable-baselines here:

https://stable-baselines.readthedocs.io/en/master/index.html


## Introduction
[BipedalWalker-v3](https://gym.openai.com/envs/BipedalWalker-v2/) is an environment in OpenAI gym. Reward is given for moving forward, total 300+ points up to the far end. If the robot falls, it gets -100.

[Stable Baselines](https://github.com/hill-a/stable-baselines) is a set of improved implementations of Reinforcement Learning algorithms based on OpenAI [Baselines](https://github.com/openai/baselines). The simplicity of these tools will allow beginners to experiment with a more advanced toolset, without being buried in implementation details.


## Experiment
In this example, four RL algorithms as below are implemented:
- PPO
- ACKTR
- SAC
- TD3

Hyperparameters were set as it is advised in [RL Baselines Zoo](https://github.com/araffin/rl-baselines-zoo).

For each algorithm, the timesteps are all two million so that we could compare them.


## Get Started
The codes of this example are wrriten using Jupyter Notebook.

You can just enter the GitHub URL of each algorithm in [Google Colab](https://colab.research.google.com/) and run them directly.


## Result
The results are shown in the TensorBorad:

