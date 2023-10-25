# Random Walk

# Continuous-Time Markov Chains (CTMCs) and Modeling

## Table of Contents
- [Introduction](#introduction)
- [Project Overview](#project-overview)
- [Part 1: Single Particle Analysis](#part-1-single-particle-analysis)
  - [1.1 Average Return Time](#11-average-return-time)
  - [1.2 Comparing to Theoretical Return Time](#12-comparing-to-theoretical-return-time)
  - [1.3 Variance of Consensus Value](#13-variance-of-consensus-value)
- [Part 2: Dual Perspective Analysis](#part-2-dual-perspective-analysis)
  - [2.1 Particle Perspective](#21-particle-perspective)
  - [2.2 Node Perspective](#22-node-perspective)
- [Usage](#usage)
- [Installation](#Installation)

## Introduction
This project focuses on the study of Continuous-Time Markov Chains (CTMCs) and their applications in modeling dynamic systems. CTMCs are essential for understanding the behavior of systems evolving over continuous time in a probabilistic manner. The project comprises two main parts: Single Particle Analysis and Dual Perspective Analysis.

## Project Overview
- **Part 1: Single Particle Analysis**
  - In this section, I analyze the behavior of a single particle performing a continuous-time random walk within a network.
  - I investigate:
    - Average time it takes a particle starting at node `𝑎` to leave the node and return to node `i`.
    - Comparison of experimental results to theoretical return times.
    - Computation of the variance of the consensus value.

- **Part 2: Dual Perspective Analysis**
  - This section provides a deeper understanding of CTMCs by examining them from two perspectives: Particle Perspective and Node Perspective.
  - I analyze:
    - How individual particles move within the network.
    - How nodes in the network influence particle transitions and dynamics.

## Usage
To get started with this project, refer to my documentation and the codebase.

## Installation
  Prerequisites libraries for this project:
   - import networkx as nx
   - import numpy as np
   - import matplotlib.pyplot as plt
