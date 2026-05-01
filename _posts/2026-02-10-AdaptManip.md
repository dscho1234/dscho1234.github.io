---
title: "[RA-L submitted] AdaptManip: Learning Adaptive Whole-Body Object Lifting and Delivery with Online Recurrent State Estimation"
categories:
 - Research
 - Conference
tags:
 - Humanoid loco-manipulation
 - Reinforcement Learning
header:
  teaser: /assets/image/thumbnail/2026RA-L_AdaptManip_thumbnail.png
conference: RA-L (IEEE Robotics and Automation Letters)
authors: Morgan Byrd, DongHoon Baek, Kartik Garg, Hyunyoung Jung, <u>Daesol Cho</u>, Maks Sorokin, Robert Wright and Sehoon Ha
links:
 - paper: 
   link: https://arxiv.org/pdf/2602.14363
   name: "Paper"

---


**Abstract:** This paper presents Adaptive Whole-body LocoManipulation, AdaptManip, a fully autonomous framework for humanoid robots to perform integrated navigation, object lifting, and delivery. Unlike prior imitation learning-based approaches that rely on human demonstrations and are often brittle to disturbances, AdaptManip aims to train a robust loco-manipulation policy via reinforcement learning without human demonstrations or teleoperation data. The proposed framework consists of three coupled components: (1) a recurrent object state estimator that tracks the manipulated object in real time under limited fieldof-view and occlusions; (2) a whole-body base policy for robust locomotion with residual manipulation control for stable object lifting and delivery; and (3) a LiDAR-based robot global position estimator that provides drift-robust localization. All components are trained in simulation using reinforcement learning and deployed on real hardware in a zero-shot manner. Experimental results show that AdaptManip significantly outperforms baseline methods, including imitation learning-based approaches, in adaptability and overall success rate, while accurate object state estimation improves manipulation performance even under occlusion. We further demonstrate fully autonomous real-world navigation, object lifting, and delivery on a humanoid robot.