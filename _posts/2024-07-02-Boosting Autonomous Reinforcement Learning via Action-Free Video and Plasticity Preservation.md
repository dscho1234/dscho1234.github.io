---
title: "[RSS 2024 workshop] Boosting Autonomous Reinforcement Learning via Action-Free Video and Plasticity Preservation"
categories:
 - Research
 - Conference
tags:
 - Autonomous RL
 - Non-episodic RL
 - Action-free data
 - Temporal representation
 - Plasticity

header:
  teaser: /assets/image/thumbnail/2024RSS_workshop_thumbnail.png
conference: RSS (Robotics Science and Systems)
authors: <u>Daesol Cho</u>, Jigang Kim and H. Jin Kim
links:
 - paper: 
   link: 
   name: "Paper"

---


**Abstract:** Despite the remarkable success of reinforcement learning (RL) in mastering intricate skills through environmental interactions, the conventional assumption of easily accessible resets at the end of each episode poses challenges for autonomous learning in real-world scenarios. This assumption has prompted an increased focus on the autonomous RL (ARL) of embodied agents, aiming to facilitate learning from non-episodic interactions. However, most of the prior ARL approaches have difficulty in handling high-dimensional inputs such as images or heavily rely on action-labeled demonstration data for action regularization towards expert behavior. In contrast, we propose an ARL algorithm that operates efficiently with minimal action-free video data. It enables the agent to learn without task-specific reward engineering and to understand the task implicitly by learning the temporal structure of the environment. Leveraging quasimetric-based temporal distance representation learning and network plasticity preservation, our method demonstrates superior performance over previous approaches without any access to the expert actions.