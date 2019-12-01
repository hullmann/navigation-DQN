# Deep Reinforcement Learning Udacity Nanodegree

# Project 1: Navigation

Navigation Project in [Deep Reinforcement Learning Udacity Nanodegree](https://www.udacity.com/course/deep-reinforcement-learning-nanodegree--nd893)

[//]: # (Image References)

[image1]: https://user-images.githubusercontent.com/10624937/42135619-d90f2f28-7d12-11e8-8823-82b970a54d7e.gif "Trained Agent"

### Project Details

In this project, the task is to train an agent to navigate and to collect bananas in a large, square world.  

![Trained Agent][image1]

A reward of +1 is provided for collecting a yellow banana, and a reward of -1 is provided for collecting a blue banana. The  goal of the agent is to collect as many yellow bananas as possible in one episode while avoiding blue bananas

The state space has 37 dimensions and contains the agent's velocity, along with ray-based perception of objects around agent's forward direction.  Given this information, the agent has to learn how to best select actions.  Four discrete actions are available, corresponding to moving forward, backward and turning left or right.


### Getting Started

1. Set up your environment according to the instructions of the [DRLND GitHub repository](https://github.com/udacity/deep-reinforcement-learning#dependencies)

2. Clone this GitHub repository [navigation-DQN](https://github.com/hullmann/navigation-DQN)

3. Install the Unity  environment from one of the links below.  You need only select the environment that matches your operating system:
    - Linux: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Linux.zip)
    - Mac OSX: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana.app.zip)
    - Windows (32-bit): [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Windows_x86.zip)
    - Windows (64-bit): [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Windows_x86_64.zip)
    
    (_For Windows users_) Check out [this link](https://support.microsoft.com/en-us/help/827218/how-to-determine-whether-a-computer-is-running-a-32-bit-version-or-64) if you need help with determining if your computer is running a 32-bit version or 64-bit version of the Windows operating system.

    (_For AWS_) If you'd like to train the agent on AWS (and have not [enabled a virtual screen](https://github.com/Unity-Technologies/ml-agents/blob/master/docs/Training-on-Amazon-Web-Service.md)), then please use [this link](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Linux_NoVis.zip) to obtain the environment.

Place the file in the DRLND GitHub repository, in the `navigation-DQN/` folder, and unzip (or decompress) the file. 

### Instructions

Follow the instructions in `Navigation.ipynb` to train your agent or scroll to the bottom of the code to let the agent run based on pretrained weights.