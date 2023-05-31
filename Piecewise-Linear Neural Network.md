---
title: "Piecewise-Linear Neural Network"
feed: show
date: 2023-05-31
alias: "PL-NN"
---

A _piecewise-linear neural network_ $$f$$ is a [[Neural Network]] for which a bounded input domain $$\mathcal{C}$$ can be decomposed into a set of polyhedra $$\mathcal{C}_i$$ such that $$\mathcal{C} = \bigcup_i \mathcal{C}_i$$ and where the restriction of $$f$$ to $$\mathcal{C}_i$$ is a linear function for each $$i$$.

This type of network represents the majority of networks used in practice.

---

# Sources
- [[Branch and Bound for Piecewise Linear Neural Network Verification]]