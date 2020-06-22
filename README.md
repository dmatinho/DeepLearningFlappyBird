# Using Q-learning & Deep Q-Network to Learn How To Play Flappy Bird

<img src="./images/flappy_bird_demp.gif" width="250">


## Overview
I presented this project presented in a Deep Learning & Image Recognition Class along with Jonathan Huff and Zeyang (Roy) Xie. This project follows the description of the Deep Q Learning algorithm described in Playing Atari with Deep Reinforcement Learning [2] and shows that this learning algorithm can be further generalized to the notorious Flappy Bird.

## Installation Dependencies:
* Python 2.7 or 3
* TensorFlow 0.7
* pygame
* OpenCV-Python


## What is Reinforcement Learning?
Machine Learning technique that enables an agent to learn in an interactive environment by trail and error using feedback from its own actions.

## What is Q-learning?
Q-learning seeks to find the best action to take given the current state in order to maximize the total reward. Q stands for ‘quality’ of a given state and action pair in gaining some reward.

## What is Deep Q-Network?
A reinforcement learning (RL) algorithm that combines Q-Learning with deep neural networks to let RL work for complex, high-dimensional environments. DQN uses a neural network to approximate the Q-values function to generalize unseen states


#### Environment
Since deep Q-network is trained on the raw pixel values observed from the game screen at each time step, [3] finds that remove the background appeared in the original game can make it converge faster. This process can be visualized as the following figure:

<img src="./images/preprocess.png" width="450">

### DQN Architecture
<img src="./images/network.png">

#### In this repository you can find:
- Q-learning approach
- DQN approach
- Validation
- Deck of the final presentation

#### Training
1. 500 and 10000 iterations for Q-Learning
2. 500 and 10000 iterations for DQN

## Disclaimer
This work is highly based on the following repos:

1. [yenchenlin/DeepLearningFlappyBird] (https://github.com/yenchenlin/DeepLearningFlappyBird)
2. [sourabhv/FlapPyBird] (https://github.com/sourabhv/FlapPyBird)
3. [asrivat1/DeepLearningVideoGames](https://github.com/asrivat1/DeepLearningVideoGames)

