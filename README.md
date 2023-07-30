# Rocket Landing Using Reinforcement Learning

## Overview

This project focuses on developing a system for rocket landing using Reinforcement Learning (RL). It is submitted as partial fulfillment of the requirements for the Bachelor's Degree of Artificial Intelligence in Information Technology.

## Abstract

Space exploration is advancing rapidly, and one of the major challenges is the safe and efficient landing of rockets. This project aims to solve the problem of incomplete or explosive landings by developing a landing system through Reinforcement Learning.

Utilizing a variant of RL called Deep Q-Network (DQN), this project trains an agent to land a rocket safely on a landing pad while minimizing fuel consumption and touchdown velocity. The agent learns to make better landing decisions through training, ultimately landing the rocket safely and efficiently.

## Objectives

- Reaching high accuracy to enhance efforts in space exploration.
- Designing and implementing a reinforcement learning algorithm for successful rocket landing.
- Customizing the GYM library environment to suit the project's goals.
- Adjusting the vehicle weight in the system to match the actual weight.
- Setting a target for landing, represented by two funnels to improve the landing process.
- Using the RL algorithm to optimize the rocket landing process for specific mission objectives.

## Methodology

The methodology includes defining the problem, selecting the RL algorithm (Deep Q-Network), implementing and testing the algorithm, optimizing and fine-tuning, extending capabilities, optimizing for specific mission objectives, evaluating performance, and documenting results.

## Algorithm

The Deep Q-Network (DQN) algorithm was chosen for this project. The reasons for choosing DQN over DDQN include its simplicity, proven track record, suitability for tasks with simple state spaces, and sufficiency for tasks that do not require high levels of accuracy.

## Implementation

The implementation includes the design of a neural network with 6 layers and 64 neurons per layer, using the ReLU activation function. The training process involves a batch size of 4 and a learning rate of 0.1, with a total of 850 epochs.

## Results

The use of DQN resulted in a score of 242, exceeding initial expectations and demonstrating the effectiveness of DQN in solving complex control and optimization tasks.

## Limitations and Challenges

- Computational complexity
- Hyperparameter tuning
- Convergence issues

## Conclusion

This project demonstrates the potential of using RL and DQN for control tasks, such as landing a rocket. It shows the effectiveness of using reinforcement learning and the DQN algorithm to control a complex system like a rocket landing.

## Authors

- Zaid Nader Ata AL-Otel
- Ammar Yaser Abed AL-Daim
- Hussam Basem Barqawi
- Mohammad Bassam Suliman Abu Amra

## Supervisor

- Dr. Yazan Alaya AL-Khassawneh

## License

This project is licensed By Zarqa university
