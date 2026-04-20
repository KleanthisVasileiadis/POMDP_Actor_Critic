# POMDP Actor-Critic

This repository contains implementations of **Actor-Critic methods in Partially Observable Markov Decision Processes (POMDPs)**.
The project was developed as part of the *Deep Reinforcement Learning* course.

The goal is to study how recurrent architectures can be used to handle partial observability and to evaluate their performance under different settings.

---

## Overview

The repository is divided into two main parts:

1. **Single-Agent Actor-Critic in POMDPs**
2. **Multi-Agent Deep Reinforcement Learning**

---

## Part 1: Single-Agent POMDPs

This section focuses on applying Actor-Critic methods in environments where the agent does not have full access to the true state.

### Key Components:

* Use of a Gym environment with partial observability
* Implementation of **Recurrent Actor-Critic models**
* Comparison between:

  * LSTM-based architectures
  * GRU-based architectures

### Experiments:

* Analysis of performance differences between LSTM and GRU
* Study of hyperparameters such as:

  * Learning rate
  * Network size
  * Activation functions

### Additional Variant:

* Feature extraction using a feedforward network before the RNN
* Comparison between:

  * RNN-first architecture
  * Feedforward-first architecture

---

## Part 2: Multi-Agent DRL

This section implements a multi-agent reinforcement learning algorithm based on the following (MADDPG) paper:

📄 https://arxiv.org/abs/1706.02275

---

## Repository Structure

* `Single_Agent/` — Recurrent Actor-Critic implementations for POMDPs
* `Multi_Agent/` — Multi-agent DRL implementation
* `Report_POMDP_Actor_critic.pdf` — Detailed report with experiments and findings

---

## Objective

The main objectives of this project are to:

* Understand decision-making under partial observability
* Evaluate the impact of recurrent architectures (LSTM vs GRU)
* Analyze the effect of architectural and training choices
* Explore multi-agent reinforcement learning settings

---
