# Deep Reinforcement Learning Project 1: Navigation

This repository contains my work for Udacity's [Deep Reinforcement Learning Nanodegree](https://www.udacity.com/course/deep-reinforcement-learning-nanodegree--nd893) Project 1: Navigation.

## Problem Statement

**The goal is to train an agent to navigate a virtual world and collect as many yellow bananas as possible while avoiding blue bananas**

![In Project 1, train an agent to navigate a large world.](images/navigation.gif)

A reward of +1 is provided for collecting a yellow banana, and a reward of -1 is provided for collecting a blue banana. Thus, the goal of your agent is to collect as many yellow bananas as possible while avoiding blue bananas.

The state-space has 37 dimensions and contains the agent's velocity, along with ray-based perception of objects around the agent's forward direction. 

Given this information, the agent has to learn how to best select actions. Four discrete actions are available, corresponding to:

- 0 - move forward.
- 1 - move backward.
- 2 - turn left.
- 3 - turn right.

The task is episodic, and **in order to solve the environment, the agent must get an average score of +13 over 100 consecutive episodes.**


### About Deep Reinforcement Learning

I have implemented a Value-Based method called [Deep Q-Networks](https://deepmind.com/research/dqn/)

[Reinforcement learning(RL)](https://en.wikipedia.org/wiki/Reinforcement_learning) is an area of machine learning concerned with how software agents ought to take actions in an environment in order to maximize the notion of cumulative reward. This is very akin to how humans actually learn things from experience through trial and error. The environments are formulated as a Markov Decision Process or MDP. RL has a wide variety of applications be it in control theory problems or robotics or finance or self-deiving cars or autonomous game-playing agents.

### Environment details

The environment is based on [Unity ML-agents](https://github.com/Unity-Technologies/ml-agents)

Note: The project environment provided by Udacity is similar to, but not identical to the [Banana Collector](https://github.com/Unity-Technologies/ml-agents/blob/master/docs/Learning-Environment-Examples.md#banana-collector) environment on the Unity ML-Agents GitHub page.

## Getting started

### Installation requirements

- First, configure a Python 3.6 / PyTorch 0.4.0 environment with the needed requirements as described in the [Udacity repository](https://github.com/udacity/deep-reinforcement-learning#dependencies)
- Clone this project and have it accessible in your Python environment
- Install the Unity environment as described in the [Getting Started section](https://github.com/udacity/deep-reinforcement-learning/blob/master/p1_navigation/README.md) (The Unity ML-agent environment is already configured by Udacity)

  - Download the required environment according to your need from the links below :
    - Linux: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Linux.zip)
    - Mac OSX: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana.app.zip)
    - Windows (32-bit): [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Windows_x86.zip)
    - Windows (64-bit): [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Windows_x86_64.zip)
    
    (_For Windows users_) Check out [this link](https://support.microsoft.com/en-us/help/827218/how-to-determine-whether-a-computer-is-running-a-32-bit-version-or-64) if you need help with determining if your computer is running a 32-bit version or 64-bit version of the Windows operating system.

    (_For AWS_) If you'd like to train the agent on AWS (and have not [enabled a virtual screen](https://github.com/Unity-Technologies/ml-agents/blob/master/docs/Training-on-Amazon-Web-Service.md)), then please use [this link](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Linux_NoVis.zip) to obtain the environment.


- Finally, unzip the environment archive in the 'project's environment' directory and eventually adjust the path to the Unity Environment in the code.
  
### Train an agent
    
Execute the provided notebook within this Nanodegree Udacity Online Workspace for "project #1  Navigation" (or build your own local environment and make necessary adjustments for the path to the UnityEnvironment in the code )

Note :
- Playing with the agent manually and watching it train in the environment has not been implemented as it is not available with Udacity Online Workspace (No Virtual Screen)    
- To watch the agent train and play in the environment run the code in your local setup
