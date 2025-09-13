---
title: "[CoRL 2025 workshop] Unifying What and How: Distilling a Pre-trained Unified Skill Representation for Efficient Adaptation"
categories:
 - Research
 - Conference
tags:
 - Skill
 - Imitation Learning
 - Vision-Language
 

header:
  teaser: /assets/image/thumbnail/2025CoRL_USR_thumbnail.pdf
conference: CoRL (International Conference on Robot Learning)
authors: Jusuk Lee, <u>Daesol Cho</u>, Jonghun Shin, Jonghae Park, Taekbeom Lee, and H. Jin Kim
links:
 - paper: 
   link: 
   name: "Paper"

---


**Abstract:** Skill abstraction, the process of learning reusable and temporally extended behaviors, has emerged as a key focus in robot learning for its potential to improve sample efficiency and generalization. However, existing methods exhibit complementary strengths and weaknesses, typically modeling either high-level semantic intent (what to do) while sacrificing motion fidelity, or fine-grained motion dynamics (how to do it) while lacking semantic context. To address these limitations, we introduce Unified Skill Representation (USR) that unifies both the semantic intent and motion dynamics into a single skill representation. USR employs a cross-modal VQ-VAE to learn a semantically grounded and dynamically aware skill codebook. Furthermore, we propose a decoupled training framework that reconciles large-scale skill pre-training with practical deployment. Our approach builds transferable skills from vast, diverse datasets and then trains a lightweight policy on small, in-domain data. Extensive experiments on the LIBERO benchmark demonstrate that USR not only achieves near expert-level performance on the training distribution but also substantially outperforms prior methods in few-shot transfer to unseen tasks. Our results highlight the importance of both unifying skill representations and decoupling the training pipeline, offering a step toward more generalizable and practical robotic agents.