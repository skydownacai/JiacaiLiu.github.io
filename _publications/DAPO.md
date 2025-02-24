---
title: "Improving Multi-Step Reasoning Abilities of Large Language Models with Direct Advantage Policy Optimization"
collection: publications
permalink: /publication/DAPO
excerpt: ''
date: 2024-12-24
venue: 'arxiv'
paperurl: 'https://arxiv.org/pdf/2412.18279'
citation: 'Jiacai Liu and Chaojie Wang and Chris Yuhao Liu and Liang Zeng and Rui Yan and Yiwen Sun and Yang Liu and Yahui Zhou. arXiv:2412.18279, 2024.'
---

The role of reinforcement learning (RL) in enhancing the reasoning of large language models (LLMs) is becoming increasingly significant. Despite the success of RL in many scenarios, there are still many challenges in improving the reasoning of LLMs. One challenge is the sparse reward, which makes optimization difficult for RL and necessitates a large amount of data samples. Another challenge stems from the inherent instability of RL, particularly when using Actor-Critic (AC) methods to derive optimal policies, which often leads to unstable training processes.  To address these issues, we introduce Direct Advantage-Based Policy Optimization (DAPO), a novel step-level offline RL algorithm for enhancing the reasoning abilities of LLMs. Unlike standard alignment that relies solely on outcome rewards to optimize policies (such as DPO),  DAPO employs a critic function to predict the reasoning accuracy at each step, thereby generating dense signals to refine the generation strategy. Additionally, the Actor and Critic components in DAPO are trained independently, avoiding the co-training instability observed in standard AC algorithms like PPO.  We train DAPO on mathematical and code problems and then evaluate its performance on multiple benchmarks. Our results show that DAPO can effectively enhance the mathematical and code capabilities on both SFT models and RL models, demonstrating the effectiveness of DAPO.