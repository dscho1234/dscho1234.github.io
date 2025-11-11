---
title: "[RA-L 2025] Single-View 3D-Aware Representations for Reinforcement Learning by Cross-View Neural Radiance Fields"
categories:
 - Research
 - Conference
tags:
 - 3D representation
 - Neural Radiance Field
 - Single-View Inference
 

header:
  teaser: /assets/image/thumbnail/2025RA-L_SinCro_thumbnail.png
conference: RA-L (IEEE Robotics and Automation Letters)
authors: <u>Daesol Cho*</u>, Seungyeon Yoo*, Dongseok Shim, and H. Jin Kim
links:
 - paper: https://sincro-ral.github.io
   link: 
   name: "Paper"

---


**Abstract:** Reinforcement learning (RL) has enabled robots to develop complex skills, but its success in image-based tasks often depends on effective representation learning. Prior works have primarily focused on 2D representations, often overlooking the inherent 3D geometric structure of the world, or have attempted to learn 3D representations that require extensive resources such as synchronized multi-view images even during deployment. To address these issues, we propose a novel RL framework that extracts 3D-aware representations from single-view RGB input, without requiring camera pose or synchronized multi-view images during the downstream RL. Our method employs an autoencoder architecture, using a masked Vision Transformer (ViT) as the encoder and a latent-conditioned Neural Radiance Fields (NeRF) as the decoder, trained with cross-view completion to implicitly capture fine-grained, 3D geometry-aware representations. Additionally, we utilize a time contrastive loss that further regularizes the learned representation for consistency across different viewpoints, which enables viewpoint-robust robot manipulations. Our method significantly enhances the RL agent's performance both in simulation and real-world experiments, demonstrating superior effectiveness compared to prior 3D-aware representation-based methods, even when using only single-view RGB images during deployment.