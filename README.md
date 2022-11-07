# Neural-Architecture-Search
Collecting ideas and testing ways to use NAS on classification problems

## 1. Network Morphing

[Jin et al. (2019)](https://arxiv.org/pdf/1806.10282.pdf)

They apply Bayesian Optimization for network morphing by designing a novel acquisition function for a tree-structured space. They not only morph the leaves of the tree structure but also the inner nodes, allowing them to morph into smaller architectures as well and avoid iteratively building bigger and more complex architectures. A* search and simulated annealing are proposed to balance exploration and exploitation. They achieve impressive results on classification tasks.
