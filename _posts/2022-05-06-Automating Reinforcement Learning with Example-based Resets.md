---
title: "[RA-L 2022, ICRA 2023] Automating Reinforcement Learning with Example-based Resets"
categories:
 - Research
 - Journal
 - Conference
tags:
 - autonomous RL
 - non-episodic

header:
  teaser: /assets/image/thumbnail/2022RA-L_Automating_thumbnail.jpg
conference: RA-L (IEEE Robotics and Automation Letters)
authors: Jigang Kim, J. hyeon Park, <u>Daesol Cho</u> and H. Jin Kim
links:
 - paper: 
   link: https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9770380
   name: "Paper"
 - video:
   link: https://www.youtube.com/watch?v=himd0Z5b64A
   name: "Video"
 - bibtex: 
   name: "Bibtex"
---

{% include video id="himd0Z5b64A" provider="youtube" %}

**Abstract:** Deep reinforcement learning has enabled robots to learn motor skills from environmental interactions with minimal to no prior knowledge. However, existing reinforcement learning algorithms assume an episodic setting, in which the agent resets to a fixed initial state distribution at the end of each episode, to successfully train the agents from repeated trials. Such reset mechanism, while trivial for simulated tasks, can be challenging to provide for real-world robotics tasks. Resets in robotic systems often require extensive human supervision and task-specific workarounds, which contradicts the goal of autonomous robot learning. In this paper, we propose an extension to conventional reinforcement learning towards greater autonomy by introducing an additional agent that learns to reset in a self-supervised manner. The reset agent preemptively triggers a reset to prevent manual resets and implicitly imposes a curriculum for the forward agent. We apply our method to learn from scratch on a suite of simulated and real-world continuous control tasks and demonstrate that the reset agent successfully learns to reduce manual resets whilst also allowing the forward policy to improve gradually over time.

## Bibtex <a id="bibtex"></a>
```
@article{kim2022automating,
  title={Automating reinforcement learning with example-based resets},
  author={Kim, Jigang and hyeon Park, J and Cho, Daesol and Kim, H Jin},
  journal={IEEE Robotics and Automation Letters},
  volume={7},
  number={3},
  pages={6606--6613},
  year={2022},
  publisher={IEEE}
}
```