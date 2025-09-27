---
layout: default
title: "Projects"
mathjax: true
---

## Projects

### Sparse Affine Projection Algorithm (SAPA)

Reducing per-iteration complexity by proposing a [sparse affine projection algorithm (SAPA)](https://ieeexplore.ieee.org/iel7/9817614/9817658/09817674.pdf):
In each iteration of the algorithm, a parity-polytope projection must be applied which is computationally intensive, with a time complexity of $O(d \log(d))$, where d is the dimension of the polytope. The proposed Sparse Affine Projection Algorithm (SAPA) approximates the projection step with great precision, such that the overall performance of the decoder is not significantly impacted while achieving a linear time complexity of $O(d)$.

### Randomized Layered Scheduling

Reducing the number of iterations by proposing a [randomized layered scheduling](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=9965857) for node updates:
Previous research in the field of iterative LDPC decoders has demonstrated the efficacy of scheduling node updates to improve convergence. While prior works have proposed deterministic strategies for scheduling updates, we proposed a randomized approach by introducing a probability mass function over the node indices. This randomized schedule allows the decoder to take advantage of the information provided by the Signal-to-Noise (SNR) ratio and adapt the schedule to fall somewhere between a completely greedy and completely agnostic schedule.