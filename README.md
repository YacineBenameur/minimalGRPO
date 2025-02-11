# minimalGRPO

## Overview

This repository provides a minimalistic implementation of the **Group Relative Policy Optimization (GRPO)** algorithm, designed for clarity and educational purposes. GRPO is a reinforcement learning method introduced by **DeepSeek**, aiming to eliminate the need for a value function. It achieves this by leveraging Monte Carlo estimates from multiple trajectories generated using the same initial random seed. For more details, refer to the original paper: [DeepSeekMath: Pushing the Limits of Mathematical Reasoning in Open Language Models](https://arxiv.org/abs/2402.03300).

## Purpose

This implementation does **not** aim to achieve state-of-the-art performance. Instead, it serves as a **starter implementation** to help individuals familiar with **classical reinforcement learning problems** (e.g., robotics and games) quickly understand and experiment with the GRPO algorithm.  

To keep it minimal and easy to follow, this implementation follows the **single-file coding style** of [minimalRL](https://github.com/seungeunrho/minimalRL). In fact, it is an **adaptation** of the excellent PPO implementation from minimalRL: [ppo.py](https://github.com/seungeunrho/minimalRL/blob/master/ppo.py).  

For those looking for a **more optimized** implementation of PPO, check out [CleanRL](https://github.com/vwxyzjn/cleanrl), which provides highly efficient and structured reinforcement learning implementations.

## Running in Google Colab

This implementation **runs directly in Google Colab** with no additional setup required.  

Simply **upload the notebook to Google Colab**, and you can run it immediately.

If you plan to run it **locally**, ensure you have the correct package versions:

- **Gymnasium**: `1.0.0`
- **Torch**: `2.5.1+cu124`
- **NumPy**: `1.26.4`
