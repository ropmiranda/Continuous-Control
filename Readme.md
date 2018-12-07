# Continuous-Control

## The Project
Reacher is the second project of Deep Reinforcement Learning Nanodegree from Udacity.
The main objective here is to solve an environment (Unity Reacher Environment) using deep reinforcement learning techniques. This project uses DDPG (Deep Deterministic Policy Gradient) to solve the environment.


## The Environment
The environment Reacher.app was develop and provided by Udacity team. The environment is composed by an agent that is a double-jointed arm which can move to target locations. The agent must move it's hand to the goal location, and keep it there. A reward of +0.1 is provided for each step that the agent's hand is in the goal location. Thus, the goal of the agent is to maintain its position at the target location for as many time steps as possible.

<p align="center"><img src="https://s3.amazonaws.com/video.udacity-data.com/topher/2018/June/5b1ea778_reacher/reacher.gif" alt="Example game of isolation" width="50%" style="middle"></p>


## The solution
To solve the problem an agent is trained using reinforcement learning techniques. The implementation is written in PyTorch and Python 3.6 that implements a DDPG in order to help training the agent. The problem is considered solved when the trained agent reaches an average of 30 points on afetr 100 episodes.


## Getting Started
In order to run this code, install the following dependencies:

`pip install unityagents`

`pip install torch`

`pip install matplotlib`

`pip install numpy`


## Download the environment
For this project, you will not need to install Unity - this is because we have already built the two environments for you, and you can download it from one of the links below. You need only select the environment that matches your operating system:

Version 1: One (1) Agent

Linux: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P2/Reacher/one_agent/Reacher_Linux.zip)

Mac OSX: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P2/Reacher/one_agent/Reacher.app.zip)

Windows (32-bit): [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P2/Reacher/one_agent/Reacher_Windows_x86.zip)

Windows (64-bit): [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P2/Reacher/one_agent/Reacher_Windows_x86_64.zip)

Version 2: Twenty (20) Agents

Linux: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P2/Reacher/Reacher_Linux.zip)

Mac OSX: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P2/Reacher/Reacher.app.zip)

Windows (32-bit): [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P2/Reacher/Reacher_Windows_x86.zip)

Windows (64-bit): [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P2/Reacher/Reacher_Windows_x86_64.zip)

## Executing the solution
Given that jupyter has been installed http://jupyter.org/install, execute the following command on terminal:
```shell
$ jupyter notebook
```
After Jupyter Notebook has opened, navegate to the directory `continuous-control/` and double click in Continuous_Control.ipynb. There you can follow the instructions to execute the solution. 

## Version 2
The second version is composed by twenty agents instead of only one. The second version is useful for algorithms like PPO, A3C, and D4PG that use multiple (non-interacting, parallel) copies of the same agent to distribute the task of gathering experience. 
