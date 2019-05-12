# About this project

This repository contains the solution to the Reacher Unity Environment ([github repository](<https://github.com/Unity-Technologies/ml-agents/blob/master/docs/Learning-Environment-Examples.md#reacher>)). This project is part of Udacity's [Deep Reinforcement Learning Nanodegree](https://www.udacity.com/course/deep-reinforcement-learning-nanodegree--nd893) program. The goal is to implement an agent that maintains its position at some target location for as many time steps as possible. The agent gets a reward of +0.1 for each time step the agent's arm is in the target location. 

The action space has 4 dimensions and each variable corresponds to a number between -1 and 1.  The state space dimension is 33.  This an episodic task. The environment is considered solve if the average score over 100 consecutive episode surpasses +30. 



# Getting Started

1. Download the environment from one of the links below.  You need only select the environment that matches your operating system:

    ### One Agent

    - Linux: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P2/Reacher/one_agent/Reacher_Linux.zip)
    - Mac OSX: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P2/Reacher/one_agent/Reacher.app.zip)
    - Windows (32-bit): [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P2/Reacher/one_agent/Reacher_Windows_x86.zip)
    - Windows (64-bit): [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P2/Reacher/one_agent/Reacher_Windows_x86_64.zip)

    

    ### 20 Agents

    - Linux: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P2/Reacher/Reacher_Linux.zip)
    - Mac OSX: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P2/Reacher/Reacher.app.zip)
    - Windows (32-bit): [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P2/Reacher/Reacher_Windows_x86.zip)
    - Windows (64-bit): [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P2/Reacher/Reacher_Windows_x86_64.zip)

    

    Place the file in the repository directory, and unzip (or decompress) the file.

2. 

# Instructions
The file `dqn_agent.py` corresponds to the agent class and includes the methods for interacting with the environment and training the agent. `model.py` contains the neural network architecture.   `Continuous_Control.ipynb`displays the solution. 
