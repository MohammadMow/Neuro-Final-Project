# Neuroscience Reinforcement Learning Project
This repository contains my work for the final reinforcement learning project for the Neuroscience of Learning, Memory and Cognition course. The goal was to implement an epsilon-greedy algorithm from scratch to find the optimal route through a reward grid.

# Project Structure
This project was done individually as a bonus to the final course grade. Careful reading of the instructions and implementation of the core epsilon-greedy algorithm concepts were required. Multiple experiments testing different parameters and training iterations were carried out. The code, results, and a report are submitted for grading based on algorithm efficiency and achieving the best possible reward accumulation.

# Introduction
A 30x30 grid containing reward values was provided. The task was to use Q-Learning techniques learned in class to train a model and devise a policy to navigate from the bottom-left corner to the top-right, moving only up or right each turn. Experiments started on smaller grids for initial development before optimizing the full size.

Implementation
The core epsilon-greedy algorithm was coded from scratch without external libraries. The state space consisted of each grid cell, with actions being up/right movements. Q-values represented expected cumulative rewards for state-action pairs under the current policy. A learning rate and discount factor were used to update values based on rewards received.

# Results
A plot of cumulative rewards versus training iterations also tracked policy improvement over time. Code, figures, and a report analyzing experiments are included for grading.
![Path](https://s8.uupload.ir/files/capture_mfxo.jpg)

