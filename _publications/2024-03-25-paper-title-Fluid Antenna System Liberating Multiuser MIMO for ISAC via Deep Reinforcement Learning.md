---
title: "Fluid Antenna System Liberating Multiuser MIMO for ISAC via Deep Reinforcement Learning"
collection: publications
category: manuscripts
permalink: /publication/2024-03-25-paper-title-Fluid Antenna System Liberating Multiuser MIMO for ISAC via Deep Reinforcement Learning
excerpt: "<img src='/images/0325.png'  style='float: right; margin: 5px;'>This paper investigates the joint optimization of port selection and precoding for a fluid antenna system (FAS)-assisted multiuser MIMO ISAC system using deep reinforcement learning to maximize the sum rate under a sensing constraint."
date: 2024-03-25
venue: 'IEEE Transactions on Wireless Communications'
paperurl: 'https://discovery.ucl.ac.uk/id/eprint/10191113/2/Wong_Fluid%20Antenna%20System%20Liberating%20Multiuser%20MIMO%20for%20ISAC%20via%20Deep%20Reinforcement%20Learning_AAM.pdf'
thumbnail: '/images/0325.png'
citation: 'Wang, Chao, et al. "Fluid antenna system liberating multiuser MIMO for ISAC via deep reinforcement learning." IEEE Transactions on Wireless Communications (2024).'
---


**Abstract**：The aim of this paper is to enhance the performance of an integrated sensing and communications (ISAC) system in the multiuser multiple-input multiple-output (MIMO) downlink in which a two-dimensional (2D) fluid antenna system (FAS) with multiple activated ports is employed at the base station (BS) to maximize the sum-rate of the downlink users subject to a sensing constraint. The unique feature of this setup is that the locations of the antenna ports at the FAS can be optimized jointly with the precoding design to achieve a higher sum-rate. The required optimization problem is however NP-hard. To overcome this, we start by considering the perfect channel state information (CSI) scenario where all the port CSI is available. Deep reinforcement learning is utilized to build an end-to-end learning framework for the joint optimization problem. In particular, by fixing the activated ports, we adopt a primal-dual based learning algorithm to design a constraint-aware neural network for optimizing the ISAC precoder. Then, by using the neural precoding network to calculate the reward, we adopt the deep reinforcement learning algorithm to design the port selection and precoder jointly. An advantage actor and critic (A2C) algorithm is proposed to train the policy, in which the actor network uses the pointer network to learn the stochastic policy and the critic network adopts the Long Short-Term Memory (LSTM) encoder architecture to learn the expected reward from the observations. Afterwards, the partial CSI case is addressed, where we propose a masked autoencoder (MAE) induced channel extrapolation for predicting all the CSI to facilitate the joint design. Simulation results demonstrate the promising performance of using FAS for multiuser MIMO and also validate the proposed learning-based scheme.
**Index Terms**: End-to-end learning, fluid antenna, integrated sensing and communication, multiuser MIMO, reinforcement learning, channel extrapolation.



<br/><img src='/images/03251.png' width = "600">

<br/><img src='/images/03252.png' width = "600">
