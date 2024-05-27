---
title: "Hybrid-Field Channel Estimation for XL-MIMO Systems with Stochastic Gradient Pursuit Algorithm"
excerpt: "We introduce two stochastic gradient pursuit (SGP)-based schemes for the XL-MIMO hybrid-field channel estimation in two scenarios. For the first scenario in which the prior knowledge of the specific proportion of the number of near-field and far-field channel paths is known, the scheme can effectively leverage the angular-domain sparsity of the far-field channels and the polar-domain sparsity of the near-field channels such that the channel estimation in these two fields can be performed separately. For the second scenario in which the proportion is not available, we propose an off-grid SGP-based channel estimation scheme, which iterates through the values of the proportion parameter based on a criterion before performing the hybrid-field channel estimation."
collection: publications
permalink: /publications/2024-05-27-Paper-title-Hybrid-Field Channel Estimation for XL-MIMO Systems with Stochastic Gradient Pursuit Algorithm
date: 2024-05-27
venue: 'IEEE Transactions on Signal Processing'
paperurl: 'https://arxiv.org/pdf/2405.15345'
thumbnail: /images/Paper/Paper12/FIG1.png
citation: 'Hao Lei, Jiayi Zhang, Zhe Wang, Bo Ai, and Derrick Wing Kwan Ng, “Hybrid-Field Channel Estimation for XL-MIMO Systems with Stochastic Gradient Pursuit Algorithm,” IEEE Transactions on Signal Processing, accepted, 2024.'
---


[Download paper here](https://zhewang77.github.io/files/Hybrid-Field Channel Estimation for XL-MIMO Systems with Stochastic Gradient Pursuit Algorithm.pdf)

**Abstract**: Extremely large-scale multiple-input multiple-output (XL-MIMO) is crucial for satisfying the high data rate requirements of the sixth-generation (6G) wireless networks. In this context, ensuring accurate acquisition of channel state information (CSI) with low complexity becomes imperative. Moreover, deploying an extremely large antenna array at the base station (BS) might result in some scatterers being located in near-field, while others are situated in far-field, leading to a hybrid-field communication scenario. To address these challenges, this paper introduces two stochastic gradient pursuit (SGP)-based schemes for the hybrid-field channel estimation in two scenarios. For the first scenario in which the prior knowledge of the specific proportion of the number of near-field and far-field channel paths is known, the scheme can effectively leverage the angular-domain sparsity of the far-field channels and the polar-domain sparsity of the near-field channels such that the channel estimation in these two fields can be performed separately. For the second scenario which the proportion is not available, we propose an off-grid SGP-based channel estimation scheme, which iterates through the values of the proportion parameter based on a criterion before performing the hybrid-field channel estimation. We demonstrate numerically that both of the proposed channel estimation schemes achieve superior performance in terms of both estimation accuracy and achievable rates while enjoying lower computational complexity compared with existing schemes. Additionally, we reveal that as the number of antennas at the UE increases, the normalized mean square error (NMSE) performances of the proposed schemes remain basically unchanged, while the NMSE performances of existing ones improve. Remarkably, even in this scenario, the proposed schemes continue to outperform the existing ones.

**Index Terms**: Hybrid-field communication, XL-MIMO, channel estimation, compressive sensing


<br/><img src='/images/Paper/Paper12/FIG1.png' width = "900">

Fig. 1: The hybrid-field communication scenario with a uniform linear array (ULA) at the BS in the XL-MIMO system, where the UE is equipped with multiple antennas. The Rayleigh distance is a widely adopted boundary to separate near-field and far-field communications.

<br/><img src='/images/Paper/Paper12/AL1.png' width = "900">

Algorithm 1: The Proposed On-grid Hybrid-field SGP Channel Estimation Scheme with Prior Knowledge of the Adjustable Parameter to Measure the Ratio of Near-Field and Far-Field Paths.

<br/><img src='/images/Paper/Paper12/AL2.png'' width = "900">

Algorithm 2: The Proposed Off-grid Hybrid-field SGP Channel Estimation Scheme without Prior Knowledge of the Adjustable Parameter to Measure the Ratio of Near-Field and Far-Field Paths.



<br/><img src='/images/Paper/Paper12/FIG2.png' width = "900">


<br/><img src='/images/Paper/Paper12/FIG3.png' width = "900">

<br/><img src='/images/Paper/Paper12/FIG4.png' width = "900">

<br/><img src='/images/Paper/Paper12/FIG5.png' width = "900">

Simulation Results


