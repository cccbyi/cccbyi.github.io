---
title: "Hybrid-Field Channel Estimation for XL-MIMO Systems with Stochastic Gradient Pursuit Algorithm"
excerpt: "We introduce two stochastic gradient pursuit (SGP)-based schemes for the XL-MIMO hybrid-field channel estimation in two scenarios. For the first scenario in which the prior knowledge of the specific proportion of the number of near-field and far-field channel paths is known, the scheme can effectively leverage the angular-domain sparsity of the far-field channels and the polar-domain sparsity of the near-field channels such that the channel estimation in these two fields can be performed separately. For the second scenario in which the proportion is not available, we propose an off-grid SGP-based channel estimation scheme, which iterates through the values of the proportion parameter based on a criterion before performing the hybrid-field channel estimation."
collection: publications
permalink: /publications/2024-05-27-Paper-title-Hybrid-Field Channel Estimation for XL-MIMO Systems with Stochastic Gradient Pursuit Algorithm
date: 2024-05-27
venue: 'IEEE Transactions on Signal Processing'
paperurl: 'https://arxiv.org/pdf/2405.15345'
thumbnail: /images/Paper/Paper10/Fig3.png
citation: 'Hao Lei, Jiayi Zhang, Zhe Wang, Bo Ai, and Derrick Wing Kwan Ng, “Hybrid-Field Channel Estimation for XL-MIMO Systems with Stochastic Gradient Pursuit Algorithm,” IEEE Transactions on Signal Processing, accepted, 2024.'
---


[Download paper here](https://zhewang77.github.io/files/Hybrid-Field Channel Estimation for XL-MIMO Systems with Stochastic Gradient Pursuit Algorithm.pdf)

**Abstract**: Extremely large-scale multiple-input multiple-output (XL-MIMO) is crucial for satisfying the high data rate requirements of the sixth-generation (6G) wireless networks. In this context, ensuring accurate acquisition of channel state information (CSI) with low complexity becomes imperative. Moreover, deploying an extremely large antenna array at the base station (BS) might result in some scatterers being located in near-field, while others are situated in far-field, leading to a hybrid-field communication scenario. To address these challenges, this paper introduces two stochastic gradient pursuit (SGP)-based schemes for the hybrid-field channel estimation in two scenarios. For the first scenario in which the prior knowledge of the specific proportion of the number of near-field and far-field channel paths is known, the scheme can effectively leverage the angular-domain sparsity of the far-field channels and the polar-domain sparsity of the near-field channels such that the channel estimation in these two fields can be performed separately. For the second scenario which the proportion is not available, we propose an off-grid SGP-based channel estimation scheme, which iterates through the values of the proportion parameter based on a criterion before performing the hybrid-field channel estimation. We demonstrate numerically that both of the proposed channel estimation schemes achieve superior performance in terms of both estimation accuracy and achievable rates while enjoying lower computational complexity compared with existing schemes. Additionally, we reveal that as the number of antennas at the UE increases, the normalized mean square error (NMSE) performances of the proposed schemes remain basically unchanged, while the NMSE performances of existing ones improve. Remarkably, even in this scenario, the proposed schemes continue to outperform the existing ones.

**Index Terms**: Hybrid-field communication, XL-MIMO, channel estimation, compressive sensing


<br/><img src='/images/Paper/Paper10/Fig1.png' width = "900">

Fig. 1: The major differences in resource allocation between near and far-field include beamforming, power control, and channel estimation. We consider a communication system with a frequency of 28GHz and an array aperture of 1m. Accordingly, the Rayleigh distance is 187m, and users are more likely located in the near-field region. The major application scenarios for near-field resource allocation include XL-MIMO systems, RIS-aided communication systems, and cell-free communication systems.

<br/><img src='/images/Paper/Paper10/Fig2.png' width = "900">

Fig. 2: Comparison of near-field and far-field channel characteristics.


<br/><img src='/images/Paper/Paper10/Fig3.png' width = "900">

Fig. 3: At the base station, the signal arrives at the receiver through resource allocation strategies such as precoding and power control, passing through the near-field channel. At the receiver, user grouping and scheduling strategies improve efficiency. Besides, we introduce three major challenges and solutions for near-field resource allocation.



<br/><img src='/images/Paper/Paper10/Fig4.png' width = "900">

Fig. 4: Near-field resource allocation problems and corresponding optimization problems and tools.



<br/><img src='/images/Paper/Paper10/Table1.png' width = "900">

Table 1: The optimization tools for near-field resource allocation and solutions include numerical optimization, heuristic optimization, and machine learning.

<br/><img src='/images/Paper/Paper10/Fig5.png' width = "900">

Fig. 5: Scenario 1: Beamforming design in XL-MIMO systems. The BS has N = 128 antennas and the carrier frequency is f = 30 GHz. Scenario 2: Power control in cell-free communication systems. The number of access points is 9, serving 6 receivers. The communication bandwidth is 20 MHz and the noise power is σ2 = −69 dBm. All transmitters transmit with a transmission power of no more than 200 mW


