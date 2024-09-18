---
title: "Model-free LQR design by Q-function learning"
collection: publications
category: manuscripts
permalink: /publication/2022-03-01-ModelFreeLQR
excerpt: 'This paper presents a sample-efficient, model-free approach to designing LQR controllers using optimization frameworks, extending to distributed control with robust performance on interconnected systems.'
date: 2022-03-01
venue: 'Automatica'
slidesurl: # 'http://academicpages.github.io/files/slides1.pdf'
paperurl: 'http://mylad13.github.io/files/Model-free LQR Design.pdf'
citation: 'Farjadnasab, M., & Babazadeh, M. (2022). Model-free LQR design by Q-function learning. Automatica, 137, 110060.'
---

Reinforcement learning methods such as Q-learning have shown promising results in the model-free design of linear quadratic regulator (LQR) controllers for linear time-invariant (LTI) systems. However, challenges such as sample-efficiency, sensitivity to hyper-parameters, and compatibility with classical control paradigms limit the integration of such algorithms in critical control applications. This paper aims to take some steps towards bridging the well-known classical control requirements and learning algorithms by using optimization frameworks and properties of conic constraints. Accordingly, a new off-policy model-free approach is proposed for learning the Q-function and designing the discrete-time LQR controller. The design procedure is based on non-iterative semi-definite programs (SDP) with linear matrix inequality (LMI) constraints. It is sample-efficient, inherently robust to model uncertainties, and does not require an initial stabilizing controller. The proposed model-free approach is extended to distributed control of interconnected systems, as well. The performance of the presented design is evaluated on several stable and unstable synthetic systems. The data-driven control scheme is also implemented on the IEEE 39-bus New England power grid. The results confirm optimality, sample-efficiency, and satisfactory performance of the proposed approach in centralized and distributed design.