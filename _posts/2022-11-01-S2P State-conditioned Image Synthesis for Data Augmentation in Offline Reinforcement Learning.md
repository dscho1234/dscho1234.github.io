---
title: "[NeurIPS 2022] S2P: State-conditioned Image Synthesis for Data Augmentation in Offline Reinforcement Learning"
categories:
 - Research
 - Conference
tags:
 - offline RL
 - image synthesis
 - data augmentation
header:
  teaser: /assets/image/thumbnail/2022NeurIPS_thumbnail.png
conference: NeurIPS (Neural Information Processing Systems)
authors: <u>Daesol Cho*, Dongseok Shim*</u> and H. Jin Kim
links:
 - paper: 
   link: https://arxiv.org/pdf/2209.15256.pdf
   name: "Paper"
 - video:
   link: https://www.youtube.com/watch?v=3mZKmvWgJE8
   name: "Video"
 - bibtex: 
   name: "Bibtex"
---

{% include video id="3mZKmvWgJE8" provider="youtube" %}

**Abstract:** Offline reinforcement learning (Offline RL) suffers from the innate distributional shift as it cannot interact with the physical environment during training. To alleviate such limitation, state-based offline RL leverages a learned dynamics model from the logged experience and augments the predicted state transition to extend the data distribution. For exploiting such benefit also on the image-based RL, we firstly propose a generative model, S2P (State2Pixel), which synthesizes the raw pixel of the agent from its corresponding state. It enables bridging the gap between the state and the image domain in RL algorithms, and virtually exploring unseen image distribution via model-based transition in the state space. Through experiments, we confirm that our S2P-based image synthesis not only improves the image-based offline RL performance but also shows powerful generalization capability on unseen tasks.

## Bibtex <a id="bibtex"></a>
```
@article{cho2022s2p,
  title={S2P: State-conditioned Image Synthesis for Data Augmentation in Offline Reinforcement Learning},
  author={Cho, Daesol and Shim, Dongseok and Kim, H Jin},
  journal={arXiv preprint arXiv:2209.15256},
  year={2022}
}
```