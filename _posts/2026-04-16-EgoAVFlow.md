---
title: "[RA-L submitted] EgoAVFlow: Robot Policy Learning with Active Vision from Human Egocentric Videos via 3D Flow"
categories:
 - Research
 - Conference
tags:
 - Active Vision
 - 3D Flow
 - Robot Manipulation
header:
  teaser: /assets/image/thumbnail/2026RA-L_EgoAVFlow_thumbnail.png
conference: RA-L (IEEE Robotics and Automation Letters)
authors: <u>Daesol Cho</u>, Yeongseok Jang, Danfei Xu, and Sehoon Ha
links:
 - paper: 
   link: https://dscho1234.github.io/egoavflow/
   name: "Paper"

---


**Abstract:** Egocentric human videos provide a scalable source of manipulation demonstrations; however, deploying them on robots requires active viewpoint control to maintain task-critical visibility, which human viewpoint imitation often fails to provide due to human-specific priors. We propose EgoAVFlow, which learns manipulation and active vision from egocentric videos through a shared 3D flow representation that supports geometric visibility reasoning and transfers without robot demonstrations. EgoAVFlow uses diffusion models to predict robot actions, future 3D flow, and camera trajectories, and refines viewpoints at test time with reward-maximizing denoising under a visibility-aware reward computed from predicted motion and scene geometry. Real-world experiments under actively changing viewpoints show that EgoAVFlow consistently outperforms prior human-demo-based baselines, demonstrating effective visibility maintenance and robust manipulation without robot demonstrations.