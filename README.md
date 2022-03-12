# Project 2: Continuous Control

### Introduction

For this project, we will work with the [Reacher](https://github.com/Unity-Technologies/ml-agents/blob/master/docs/Learning-Environment-Examples.md#reacher) environment.

we will start the environment, where a double-jointed arm can move to target locations. For each time step, a reward of +0.1 is given when the agent's hand is in the goal location. The objective of the agent, therefore, is to maintain its position at the target location for as many time steps as possible.

The observation space consists of 33 variables corresponding to position, rotation, velocity, and angular velocities of the arm. Each action is a vector with four numbers, corresponding to torque applicable to two joints. Every entry in the action vector should be a number between -1 and 1.

### Training

This project will use a single agent.

### Solving the Environment

The task is episodic. For the single agent option, a solution is considered valid if the agent achieves an average score of +30 over 100 consecutive episodes.


### Getting Started

1. Download the environment from one of the links below.  You need only select the environment that matches your operating system:

    - **_Version 1: One (1) Agent_**
        - Linux: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P2/Reacher/one_agent/Reacher_Linux.zip)
        - Mac OSX: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P2/Reacher/one_agent/Reacher.app.zip)
        - Windows (32-bit): [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P2/Reacher/one_agent/Reacher_Windows_x86.zip)
        - Windows (64-bit): [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P2/Reacher/one_agent/Reacher_Windows_x86_64.zip)
  
2. Place the file in ‘p2_continuous-control/` folder where ‘Continuous_Control.ipynb’ is located and unzip (or decompress) the file. Note the location of ‘Reacher.exe’ in ‘..\Reacher_Windows_x86_64\Reacher_Windows_x86_64\Reacher.exe’

### Instructions

Open Anaconda Prompt. Navigate to the folder where ‘Continuous_Control.ipynb’ file is located. Type ‘conda activate drlnd’ to activate the environment and load relevant packages. Then type ‘jupyter notebook’. A web browser will appear with the Jupyter homepage. Select ‘Continuous_Control.ipynb’. Enter the path to ‘Reacher.exe’ in the second code window. Go to Cell tab in the menu bar and select Run All. If a package is missing during code execution, exit back to prompt and type ‘conda install package-name’. The restart Jupyter Notebook.  

