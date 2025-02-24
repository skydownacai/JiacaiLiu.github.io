---
title: "On the Convergence of Projected Policy Gradient for Any Constant Step Sizes"
collection: publications
permalink: /publication/PPG
excerpt: ''
date: 2023-11-02
venue: 'arxiv'
paperurl: 'https://arxiv.org/abs/2311.01104'
citation: ' Jiacai Liu, Wenye Li, and Ke Wei. On the Convergence of Projected Policy Gradient for Any Constant Step Sizes. arXiv:2311.0110, 2023.'
---

Projected policy gradient (PPG) is a basic policy optimization method in reinforcement learning. Given access to exact policy evaluations, previous studies have established the sublinear convergence of PPG for sufficiently small step sizes based on the smoothness and the gradient domination properties of the value function. However, as the step size goes to infinity, PPG reduces to the classic policy iteration method, which suggests the convergence of PPG even for large step sizes. In this paper, we fill this gap and show that PPG admits a sublinear convergence for any constant step sizes. Due to the existence of the state-wise visitation measure in the expression of policy gradient, the existing optimization-based analysis framework for a preconditioned version of PPG (i.e., projected Q-ascent) is not applicable, to the best of our knowledge. Instead, we proceed the proof by computing the state-wise improvement lower bound of PPG based on its inherent structure. In addition, the finite iteration convergence of PPG for any constant step size is further established, which is also new.