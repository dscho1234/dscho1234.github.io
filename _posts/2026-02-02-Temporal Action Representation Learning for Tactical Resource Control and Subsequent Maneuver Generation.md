---
title: "[ICRA 2026] Temporal Action Representation Learning for Tactical Resource Control and Subsequent Maneuver Generation"
categories:
 - Research
 - Conference
tags:
 - Reinforcement Learning
 - Temporal Representation
header:
  teaser: /assets/image/thumbnail/2026ICRA_TART_thumbnail.png
conference: ICRA (International Conference on Robotics & Automation)
authors: Hoseong Jung, Sungil Son, <u>Daesol Cho<u>, Jonghae Park, Changhyun Choi and H. Jin. Kim
links:
 - paper: 
   link: 
   name: "Paper"

---


**Abstract:** Autonomous robotic systems should reason about resource control and its impact on subsequent maneuvers, especially when operating with limited energy budgets or restricted sensing. Learning-based control is effective in handling complex dynamics and represents the problem as a hybrid action space unifying discrete resource usage and continuous maneuvers. However, prior works on hybrid action space have not sufficiently captured the causal dependencies between resource usage and maneuvers. They have also overlooked the multi-modal nature of tactical decisions, both of which are critical in fast-evolving scenarios. In this paper, we propose TART, a Temporal Action Representation learning framework for Tactical resource control and subsequent maneuver generation. TART leverages contrastive learning based on a mutual information objective, designed to capture inherent temporal dependencies in resource-maneuver interactions. These learned representations are quantized into discrete codebook entries that condition the policy, capturing recurring tactical patterns and enabling multi-modal and temporally coherent behaviors. We evaluate TART in two domains where resource deployment is critical: (i) a maze navigation task where a limited budget of discrete actions provides enhanced mobility, and (ii) a high-fidelity air combat simulator in which a F-16 agent operates weapons and defensive systems in coordination with flight maneuvers. Across both domains, TART consistently outperforms hybrid-action baselines, demonstrating its effectiveness in leveraging limited resources and producing context-aware subsequent maneuvers.