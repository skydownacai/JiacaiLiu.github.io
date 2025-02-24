---
title: "$phi$-Update: A Class of Policy Update Methods with Policy Convergence Guarante"
collection: publications
permalink: /publication/phi-update
excerpt: ''
date: 2024-09-04
venue: 'ICLR'
paperurl: 'https://openreview.net/pdf?id=fh7GYa7cjO'
citation: 'Wenye Li, Jiacai Liu and Ke Wei. $\phi$-Update: A Class of Policy Update Methods with Policy Convergence Guarante. In The Thirteen International Conference on
Learning Representations, ICLR 2025, Singapore.'
---

Inspired by the similar update pattern of softmax natural policy gradient and Hadamard policy gradient, we propose to study a general policy update rule called $\phi$-update, where $\phi$ refers to a scaling function on advantage functions. Under very mild conditions on $\phi$, the global asymptotic state value convergence of $\phi$-update is firstly established. Then we show that the policy produced by $\phi$-update indeed converges, even when there are multiple optimal policies.  This is in stark contrast to existing results where explicit   regularizations  are required to guarantee the convergence of the policy.  Since softmax natural policy gradient is an instance of $\phi$-update, it provides an affirmative answer to the question whether the policy produced by softmax natural policy gradient converges. The exact asymptotic convergence rate of state values is further established based on the policy convergence. Lastly, we establish the global linear convergence of $\phi$-update.