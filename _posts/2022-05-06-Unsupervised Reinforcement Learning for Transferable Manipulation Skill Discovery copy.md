---
title: "[RA-L 2022, IROS 2022] Unsupervised Reinforcement Learning for Transferable Manipulation Skill Discovery"
categories:
 - Research
 - Journal
 - Conference
tags:
 - unsupervised RL
 - skill discovery
 - transfer learning
header:
  teaser: /assets/image/thumbnail/2022RA-L_Unsupervised_thumbnail.png
conference: RA-L (IEEE Robotics and Automation Letters)
authors: <u>Daesol Cho, Jigang Kim</u> and H. Jin Kim
links:
 - paper: 
   link: https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9770346
   name: "Paper"
 - video:
   link: https://www.youtube.com/watch?v=bF3Y4WXfM7c
   name: "Video"
 - bibtex: 
   name: "Bibtex"
---

{% include video id="bF3Y4WXfM7c" provider="youtube" %}

**Abstract:** Current reinforcement learning (RL) in robotics often experiences difficulty in generalizing to new downstream tasks due to the innate task-specific training paradigm. To alleviate it, unsupervised RL, a framework that pre-trains the agent in a task-agnostic manner without access to the task-specific reward, leverages active exploration for distilling diverse experience into essential skills or reusable knowledge. For exploiting such benefits also in robotic manipulation, we propose an unsupervised method for transferable manipulation skill discovery that ties structured exploration toward interacting behavior and transferable skill learning. It not only enables the agent to learn interaction behavior, the key aspect of the robotic manipulation learning, without access to the environment reward, but also to generalize to arbitrary downstream manipulation tasks with the learned task-agnostic skills. Through comparative experiments, we show that our approach achieves the most diverse interacting behavior and significantly improves sample efficiency in downstream tasks including the extension to multi-object, multitask problems.

## Bibtex <a id="bibtex"></a>
```
@article{cho2022unsupervised,
  title={Unsupervised Reinforcement Learning for Transferable Manipulation Skill Discovery},
  author={Cho, Daesol and Kim, Jigang and Kim, H Jin},
  journal={IEEE Robotics and Automation Letters},
  volume={7},
  number={3},
  pages={7455--7462},
  year={2022},
  publisher={IEEE}
}
```