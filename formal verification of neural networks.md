---
title: "formal verification of neural networks"
feed: show
date: 2023-05-31
alias: "neural network verification"
---

Formal verification for neural networks is the problem of, given a [[Neural Network]] implementing a function $$\mathbf{\hat{x}_n} = f(\mathbf{x_0})$$, a bounded input domain $$\mathcal{C}$$, and a property $$P$$, proving

$$\mathbf{x_0} \in \mathcal{C},\quad \mathbf{\hat{x}_n} = f(\mathbf{x_0}) \Rightarrow P(\mathbf{\hat{x}_n})$$

Properties can be represented as Boolean formulas over linear equalities that constrain the network's behaviour.

Examples for properties include [[local robustness]] and [[global robustness]].

---

# Sources
- [[Branch and Bound for Piecewise Linear Neural Network Verification]]