# Lunar Lander with Deep Q-Learning

This project implements a Deep Q-Learning agent to solve the Lunar Lander environment from OpenAI Gym (now Gymnasium).

## Description

The goal of the Lunar Lander is to land a spacecraft safely on the lunar surface. The agent receives rewards for landing successfully and penalties for crashing or using too much fuel. Deep Q-Learning is used to train the agent to make optimal decisions in this environment.

## Requirements

- Python 3.6 or higher
- Gymnasium
- PyTorch
- NumPy

## Installation

1. Clone the repository: `git clone <repository_url>`

## Usage

To train the agent, run the notebook

## Results

The agent is trained over n episode where n is configurable and in the end the landing can be visualized using glob.

## Hyperparameters

The following hyperparameters are used:

- Learning rate: 5e-4
- Minibatch size: 100
- Discount factor: 0.99
- Replay buffer size: 1e5
- Interpolation parameter: 1e-3

## Credits

- This project is based on the Deep Q-Learning tutorial by Udacity.
- The Lunar Lander environment is provided by OpenAI Gym (now Gymnasium).
