---
title: "QoS-Aware Precoder Optimization for Radar Sensing and Multiuser Communications Under Per-Antenna Power Constraints"
collection: publications
category: manuscripts
permalink: /publication/2023-05-24-paper-title-QoS-Aware Precoder Optimization for Radar Sensing and Multiuser Communications Under Per-Antenna Power Constraints
excerpt: "<img src='/images/0524.png' style='float: right; margin: 5px;'>We proposes a symbol-level precoding-based scheme for STAR-RIS-aided dual-functional radar-communications (DFRC) systems. The aim is to securely transmit confidential information and perform target sensing concurrently. A joint optimization problem is formulated to maximize the average received radar sensing power, subject to constraints on communication users' quality-of-service and security, as well as practical waveform design restrictions."
date: 2023-05-24
venue: 'IEEE Transactions on Wireless Communications'
paperurl: 'https://discovery.ucl.ac.uk/id/eprint/10172154/1/T-SP-30232-2023%20%28Chao%20Wang%29.pdf'
citation: 'Wang C, Li Z, Al-Dhahir N, et al. QoS-aware precoder optimization for radar sensing and multiuser communications under per-antenna power constraints[J]. IEEE Transactions on Signal Processing, 2023, 71: 2235-2250.'
---



**Abstract**: In this work, we concentrate on designing the precoder for the multiple-input multiple-output (MIMO) dual functional radar-communication (DFRC) system, where the dual-functional waveform is designed for performing multiuser downlink transmission and radar sensing simultaneously. Specifically, considering the signal-independent interference and signal-dependent clutter, we investigate the optimization of transmit precoding for maximizing the sensing signal-to-interference-plus-noise ratio (SINR) at the radar receiver under the constraint of the minimum SINR received at multiple communication users and per-antenna power budget. The formulated problem is challenging to solve due to the nonconovex objective function and nonconvex per-antenna power constraint. In particular, for the signal-independent interference case, we propose a distance-majorization induced algorithm to approximate the nonconvex problem as a sequence of convex problems whose optima can be obtained in closed form. Subsequently, our complexity analysis shows that our proposed algorithm has a much lower computational complexity than the widely-adopted semidefinite relaxation (SDR)-based algorithm. For the signal-dependent clutter case, we employ the fractional programming to transform the nonconvex problem into a sequence of subproblems, and then we propose a distance-majorization based algorithm to obtain the solution of each subproblem in closed form. Finally, simulation results confirm the performance superiority of our proposed algorithms when compared with the SDR-based approach. In conclusion, the novelty of this work is to propose an efficient algorithm for handling the typical problem in designing the DFRC precoder, which achieves better performance with a much lower complexity than the state-of-the-art algorithm.


**Index Terms**: Dual-functional radar-communication, radar sensing, transmit precoding, signal-independent interference,signal-dependent clutter


<br/><img src='/images/QOS1.png' width = "600">

<br/><img src='/images/QOS2.png' width = "600">
