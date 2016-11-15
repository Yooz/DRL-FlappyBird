
## Playing Flappy Bird Using Dueling Network Architectures (improved standard Deep Q network DQN)

## Implementation of Dueling Network Architectures

This code is based on the **mxnet** implementation of [DRL-FlappyBird](https://github.com/li-haoran/DRL-FlappyBird) by @li-haoran.

The dueling network architectures described at this repo are from the ICML 2016 best paper presented by Google Deepmind.

>[Dueling Network Architectures for Deep Reinforcement Learning](https://arxiv.org/pdf/1511.06581v3.pdf), Ziyu Wang, Tom Schaull, Matteo Hessel, Hado van Hasselt, Marc Lanctot and Nando de Freitas, Google Deepmind, 2016.


To run the code, just type python FlappyBirdDQN.py

You can migrate the DQN algorithm and Dueling architecture to any other environment.

## About the code

As a reinforcement learning problem, we knows we need to obtain observations and output actions, and the 'brain' do the processing work.

Therefore, you can easily understand the BrainDQN.py code. There are three interfaces:

1. getInitState() for initialization
2. getAction()
3. setPerception(nextObservation,action,reward,terminal)

the game interface just need to be able to feed the action to the game and output observation,reward,terminal


## MISC
This work is based on the repo: [yenchenlin1994/DeepLearningFlappyBird](https://github.com/yenchenlin1994/DeepLearningFlappyBird.git) (Tensorflow version) and [DRL-FlappyBird](https://github.com/li-haoran/DRL-FlappyBird) (Mxnet version).
I completed this code when I was an intern at Horizon Robotics. Greately thanks my mentors Jian Zhang and Lixin Cao, and other colleagues (Yifeng Geng, Lichao Huang) for helpful discussion. 

