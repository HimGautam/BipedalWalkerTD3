# BipedalWalkerTD3

This project is my own implementation of TD3 [paper](https://arxiv.org/pdf/1802.09477v3.pdf) for solving continuous control problem in the Bipedal Walker environment of OpenAI Gym.

![ezgif com-gif-maker (4)](https://user-images.githubusercontent.com/70597091/173229611-91dc7032-5a09-4f1e-8bb3-9ae6086eb5d7.gif)

# Overview

Twin Delayed Deep Deterministic Policy Gradient (TD3) is an Actor Critic reinforcement learning algorithm. This algorithm is an improved version of Deep Deterministic Policy Gradient. It uses 2 critic networks to limit the overestimation bias. Further, it uses delayed policy and target networks updates to reduce per-update error. 

# Requirements

This project requires following dependencies:

1. Python
2. Tensorflow
3. Numpy
4. OpenAI Gym
5. Jupyter Notebook (optional)

# Trying Out

For trying out, download the weights from repository and put them in the same folder. Run all cells except the Training cell with comment ```#Training``` on top.
