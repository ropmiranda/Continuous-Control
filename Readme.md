# Continuous-Control

## The Project
Banana Collector is the first project of Deep Reinforcement Learning Nanodegree from Udacity.
The main objective here is to solve an environment (Unity Banana Environment) using deep reinforcement learning techniques.


## The Environment
The environment banana.app was develop and provided by Udacity team. The environment is composed by and agent that has to collect yellow bananas avoiding blue bananas. The yellow bananas give the agent +1 as reward whereas the blue ones give it -1. The state space has 37 dimensions containing the agent’s velocity, along with a ray-based perception of the environment. The agent has to learn how select actions during training interactions. Move backward or forward and turn left or right are the 4 actions available.

<p align="center"><img src="https://user-images.githubusercontent.com/10624937/42135619-d90f2f28-7d12-11e8-8823-82b970a54d7e.gif" alt="Example game of isolation" width="50%" style="middle"></p>

## The solution
To solve the problem an agent is trained using reinforcement learning techniques. The implementation is written in PyTorch and Python 3.6 that implements a Deep Q-Network in order to help training the agent. The problem is considered solved when the trained agent reaches an average of 13 points on afetr 100 episodes.


## Getting Started
In order to run this code, install the following dependencies:

`pip install unityagents`

`pip install torch`

`pip install matplotlib`

`pip install numpy`

## Download the environment
For this project, you will not need to install Unity - this is because we have already built the environment for you, and you can download it from one of the links below. You need only select the environment that matches your operating system:

Linux: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Linux.zip)

Mac OSX: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana.app.zip)

Windows (32-bit): [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Windows_x86.zip)

Windows (64-bit): [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Windows_x86_64.zip)

## Executing the solution
Given that jupyter has been installed http://jupyter.org/install, execute the following command on terminal:
```shell
$ jupyter notebook
```
After Jupyter Notebook has opened, navegate to the directory `banana-collector/` and double click in Navegation.ipynb. There you can follow the instructions to execute the solution. 

## Dueling DQN
Try to use other king of network implementation:

`dueling_dqn.py`

Just little changes on the dqn_agent.py init function and an import are necessary.
