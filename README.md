# Deep Q-Network for Super Mario Bros

![Mario GIF](images/Mario%20gif.gif)




## Overview 

This project implements a Deep Q-Network to train an AI agent to play Super Mario Bros using reinforcement learning. The model leverages convoulutional neural networks (CNNs) to approximate the Q-table and improve decision-making based on previous game states.

## Installation

Requirements:

```bash
pip install torch gym gym-supeun the following command to start training:r-mario-bros nes-py opencv-python numpy matplotlib seaborn tensorboard
```

### 1. Train the model 

Run the follwing command to start training:
```bash
python main.py
```
This will train the AI agent for 50,000 episodes.

### 2. Watch the Trained Agent

Once trained, you can run the model and waatch it play:
```bash
python main.py --play
```

## Key Hyperparameters

| Parameter           | Value  |
| ------------------- | ------ |
| Learning Rate (lr)  | 1e-4   |
| Discount Factor (γ) | 0.99   |
| Memory Size         | 10,000 |
| Batch Size          | 32     |
| Epsilon Decay       | 0.9995 |
| Minimum Epsilon     | 0.05   |


Enjoy!!