---
title: "[NeurIPS 2025] Periodic Skill Discovery"
categories:
 - Research
 - Conference
tags:
 - Skill Discovery
 - Unsupervised RL
header:
  teaser: /assets/image/thumbnail/2025NeurIPS_PSD_thumbnail.jpg
conference: NeurIPS (Neural Information Processing Systems)
authors: Jonghae Park, <u>Daesol Cho</u>, Jusuk Lee, Dongseok Shim, Inkyu Jang, and H. Jin Kim
links:
 - paper: 
   link:
   name: "Paper"

---


**Abstract:** Unsupervised skill discovery in reinforcement learning (RL) aims to learn diverse behaviors without relying on external rewards. However, current methods often overlook the periodic nature of learned skills, focusing instead on increasing the mutual dependency between states and skills or maximizing the distance traveled in latent space. Considering that many robotic tasks—particularly those involving locomotion—require periodic behaviors across varying timescales, the ability to discover diverse periodic skills is essential. Motivated by this, we propose Periodic Skill Discovery (PSD), a framework that discovers periodic behaviors in an unsupervised manner. The key idea of PSD is to train an encoder that maps states to a circular latent space, thereby naturally encoding periodicity in the latent representation. By capturing temporal distance, PSD can effectively learn skills with diverse periods in complex robotic tasks, even with pixel-based observations. We further show that these learned skills achieve high performance on downstream tasks such as hurdling. Moreover, integrating PSD with an existing skill discovery method offers more diverse behaviors, thus broadening the agent’s repertoire.