# Rainbow Deep Q-Network from Scratch

Welcome to my repository for the Rainbow Deep Q-Network (DQN) implementation! Here, I share my work on this state-of-the-art reinforcement learning algorithm, built entirely from scratch using PyTorch.

## Contents

### Rainbow DQN Project

- This project is an in-depth implementation of the **Rainbow Deep Q-Network (DQN)**, combining several key enhancements over the standard DQN:

  - **Noisy DQN** for parameter noise in exploration.
  - **Dueling DQN** to separately estimate state value and advantage functions, improving the stability and learning efficiency.
  - **N-Step DQN** for faster training efficiency ( use relatively small steps).
  - **Prioritized Experience Replay** to prioritize important transitions.

- The architecture and methods implemented are inspired by the paper **[Rainbow: Combining Improvements in Deep Reinforcement Learning](https://arxiv.org/abs/1710.02298)**.
- **PyTorch Ignite** is used for monitoring, logging with tensorboard logger, and managing the training process.
- **PTAN** (link: [PTAN GitHub Repository](https://github.com/Shmuma/ptan)) is utilized for utility functions,code organization , and efficient implementation of priority replay buffer.

### Tasks to Do

- Evaluate the performance of the Rainbow DQN on different environments.
- Experiment with different hyperparameter settings to optimize the algorithm further.
- Use Ray for hyper parameter tuning

## How to Run the Code

### On Local Machine

If you have a CUDA-powered machine and want to run this project locally, follow these steps:

#### Windows

```batch
conda env create -f environment.yml -n rainbow_dqn_env
conda activate rainbow_dqn_env
```

### Notice

- Make sure you have Conda installed.
- The project is compatible with Python 3.11.

## References

Here are some key resources that guided this implementation:

- **[Rainbow: Combining Improvements in Deep Reinforcement Learning](https://arxiv.org/abs/1710.02298)**
  - Description: This paper introduces Rainbow DQN, which integrates several enhancements into the DQN framework, resulting in a more robust and efficient RL algorithm.

## Collaboration :

- I will be very glad to collaborate on this project or similar RL projects , please contact me for any collaboration opportunity

## Final Word

- I hope this project serves as a useful resource for anyone interested in reinforcement learning and deep Q-networks. Feel free to reach out if you have any questions or want to discuss AI and reinforcement learning!
