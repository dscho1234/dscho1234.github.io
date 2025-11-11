---
title: "[IROS 2025] Leveraging Temporally Extended Behavior Sharing for Multi-task Reinforcement Learning"
categories:
 - Research
 - Conference
tags:
 - Multi-Task RL
 - Exploration
 

header:
  teaser: /assets/image/thumbnail/2025IROS_thumbnail.png
conference: IROS (International Conference on Intelligent Robots and Systems)
authors: Gawon Lee, <u>Daesol Cho</u>, and H. Jin Kim
links:
 - paper: https://arxiv.org/pdf/2509.20766
   link: 
   name: "Paper"

---


**Abstract:** Multi-task reinforcement learning (MTRL) offers a promising approach to improve sample efficiency and generalization by training agents across multiple tasks, enabling knowledge sharing between them. However, applying MTRL to robotics remains challenging due to the high cost of collecting diverse task data. To address this, we propose MT-L´evy, a novel exploration strategy that enhances sample efficiency in MTRL environments by combining behavior sharing across tasks with temporally extended exploration inspired by L´evy flight. MT-L´evy leverages policies trained on related tasks to guide exploration towards key states, while dynamically adjusting exploration levels based on task success ratios. This approach enables more efficient state-space coverage, even in complex robotics environments. Empirical results demonstrate that MT-L´evy significantly improves exploration and sample efficiency, supported by quantitative and qualitative analyses. Ablation studies further highlight the contribution of each component, showing that combining behavior sharing with adaptive exploration strategies can significantly improve the practicality of MTRL in robotics applications.