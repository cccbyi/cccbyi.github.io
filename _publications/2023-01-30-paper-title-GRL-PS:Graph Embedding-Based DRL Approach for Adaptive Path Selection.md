---
title: "GRL-PS:Graph Embedding-Based DRL Approach for Adaptive Path Selection"
collection: publications
category: manuscripts
permalink: /publication/2023-01-30-paper-title-GRL-PS:Graph Embedding-Based DRL Approach for Adaptive Path Selection
excerpt: "<img src='/images/0130.png'  style='float: right; margin: 5px;'> "This paper proposes a graph embedding-based deep reinforcement learning (DRL) framework called GRL-PS for adaptive path selection in dynamic networks. It incorporates graph-structured topological information into the DRL agent’s decision-making process and uses potential-based reward shaping to accelerate learning. Experiments show that GRL-PS achieves nearly optimal performance in terms of latency and throughput, especially in large-scale dynamic networks with frequent topology changes and link failures.
date: 2023-01-30
venue: 'IEEE Transactions on Network and Service Management'
paperurl: 'https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10029936'
citation: 'Wei, Wenting, et al. "GRL-PS: Graph embedding-based DRL approach for adaptive path selection." IEEE Transactions on Network and Service Management 20.3 (2023): 2639-2651.'
---


**Abstract**：Forwarding path selection for data traffic is one of the most fundamental operations in computer networks, whose performance drastically impacts both transmission efficiency and reliability in network domains. Although deep reinforcement learning (DRL) has attracted considerable attention for path selection instead of hand-tuned heuristics, few works have con sidered how to exploit graph-structured information in networks to improve routing and forwarding efficiency. In fact, generating routes is essentially a process for finding a subgraph in a graph structured network. To this end, this paper proposes an effective and novel graph embedding-based DRL framework for adaptive path selection (termed GRL-PS), aiming at reducing end-to end (E2E) latency and promoting network throughput while maintaining stability in dynamically changing environments. Specifically, graph representation learning (GRL) is deployed as an effective enabler for the DRL agent to learn the relational knowledge of interacting entities for route decisions in networks. However, training such an agent in a dynamically changing envi ronment encounters a knowledge acquisition bottleneck, since the DRL agent is always forced to learn every task from scratch. To improve the adaptation of behaviors and acquire skills beyond what the source policy can teach, we introduce potential-based reward shaping as a means of knowledge transfer to guide the agent in unfamiliar conditions with sparse rewards. Experimental results show that compared with baseline methods, our solution can achieve nearly-optimal performance with both latency and throughput, especially in large-scale dynamic networks.
**Index Terms**: Forwarding path selection, adaptive path selec tion, deep reinforcement learning, graph representation learning



<br/><img src='/images/01301.png' width = "600">

