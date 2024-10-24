---
title: "CATMiP: Cooperative and Asynchronous Transformer-based Mission Planning for Heterogeneous Teams of Mobile Robots"
excerpt: "The CATMiP framework in the distributed execution phase.<br/><img src='/images/CATMiP(Distributed).png'>"
collection: portfolio
---
Coordinating heterogeneous teams of mobile robots for tasks such as search and rescue is highly challenging. This is due to the complexities of perception, decision making and planning in such environments, with agents' non-synchronous operation, constrained communication, and limited computational resources. This paper presents the Cooperative and Asynchronous Transformer-based Mission Planning (CATMiP) framework. CATMiP leverages multi-agent reinforcement learning (MARL) to effectively coordinate agents with heterogeneous sensing, motion, and actuation capabilities. The framework introduces a Class-based Macro-Action Decentralized Partially Observable Markov Decision Process (CMD-POMDP) to handle asynchronous decision-making among different agent classes via macro-actions. It also extends the Multi-Agent Transformer (MAT) architecture to facilitate distributed, ad-hoc communication among the agents. CATMiP easily adapts to mission complexities and communication constraints and scales to the environment and team sizes. Simulations demonstrate the framework's effectiveness in achieving cooperative mission objectives with two classes of explorer and rescuer agents, even in presence of communication and agent loss.

## Framework

![CATMiP in centralized training and distributed execution phases](/images/CATMiP.png "Figure 1 - (a) The centralized training workflow of the CATMiP framework in a simulated mission episode. (b) Implementation of the CATMiP framework on a single robot during the execution phase, where robots share mapping information and their embedded macro-observations to generate new actions in a distributed way.")

### Asynchronous Multi-Agent Transformer


![Centralized training of AMAT](/images/AMAT(Centralized).png "Figure 2 - Centralized macro-action inference as a part of the training process of AMAT. During distributed execution, the broker robot receives macro-observation embeddings from connected agents and transmits the newly obtained MAs back to them.")

## Simulation Results
<img src="/images/catmip_simulation.gif" width="330" height="330" />

[See the code here.](https://github.com/mylad13/CATMiP)

The preprint is now published on [arXiv!](https://arxiv.org/abs/2410.06372)