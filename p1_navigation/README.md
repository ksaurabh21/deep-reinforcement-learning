[//]: # (Image References)

[image1]: https://user-images.githubusercontent.com/10624937/42135619-d90f2f28-7d12-11e8-8823-82b970a54d7e.gif "Trained Agent"

# Project 1: Navigation

### Introduction

The environment is a square world with yellow and blue bananas scattered randomly. The agent's goal is to collect as many yellow bananas as possible. Collecting a yellow banana gets the agent a reward of +1 and a blue banana fetches -1. The state space has 37 dimensions which contains agent's velocity along with ray-based perception of objects around agents forward direction. The agent has 4 possible discreet actions: 
- **`0`** - move forward.
- **`1`** - move backward.
- **`2`** - turn left.
- **`3`** - turn right.

The task is episodic, and in order to solve the environment, the agent must get an average score of +13 over 100 consecutive episodes.

![Trained Agent][image1]


### Setup

To setup the environment, follow the instructions here: https://github.com/udacity/deep-reinforcement-learning#dependencies

I did this project setup on a windows 64 machine. Based on my experience, you would need Microsoft build tools installed and swig.exe available in the path variable for the setup to go smoothly.

To download the banana app, use these instructions:
Download the environment from one of the links below. You need only select the environment that matches your operating system:
- Linux: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Linux.zip)
- Mac OSX: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana.app.zip)
- Windows (32-bit): [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Windows_x86.zip)
- Windows (64-bit): [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Windows_x86_64.zip)


Then get the Navigation.ipynb, model.py and dqn_agent.py from this repository and place it in p1_navigation folder.

### Instructions

Once the above setup is done, then open a command prompt, go to p1_navigation folder and launch a jupyter notebook.
Before running code in a notebook, change the kernel to match the drlnd environment by using the drop-down Kernel menu.


