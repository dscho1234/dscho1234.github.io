---
title: "[RSS 2024 workshop] Temporal Action Representation Learning for Aerial Maneuvering and Resource-Aware Decision-Making"
categories:
 - Research
 - Conference
tags:
 - Hybrid action space
 - Temporal action representation
 

header:
  teaser: /assets/image/thumbnail/2025RSS_workshop_thumbnail.png
conference: RSS (Robotics Science and Systems)
authors: Hoseong Jung, Sungil Son, <u>Daesol Cho</u>, Jonghae Park, Changhyun Choi, and H. Jin Kim
links:
 - paper: 
   link: "https://openreview.net/forum?id=6i2sBsa1wM"
   name: "Paper"

---


**Abstract:** A fully autonomous agent should reason about how to deploy limited resources effectively in dynamic and uncertain environments. Despite the focus on learning to act under such constraints, the tactical use of resources in fast-evolving scenarios (e.g., air combat) remains underexplored. Addressing this challenge requires modeling how resource usage unfolds over time and influences future behavior. To this end, we explore self-supervised learning approaches tailored to modeling the causal dependency and temporal relationship between these interrelated processes. Specifically, we introduce TART, a temporal action contrastive learning approach that facilitates semantic alignment between resource control and tactical maneuvers. TART learns via contrastive learning based on a mutual information objective, carefully designed to account for both forward and backward dependencies embedded within such dynamics. These learned representations are quantized into discrete codebook entries that serve as inputs to the policy, enabling the evaluation of tactical decision-making in downstream tasks. To empirically assess our method, we present an air combat simulation environment where tactical resource allocation is essential for mission success, using customized scenarios of varying difficulty to compare against baseline approaches. Extensive experiments demonstrate the effectiveness of TART in the use of limited resources and superior performance in generating tactical maneuvers.