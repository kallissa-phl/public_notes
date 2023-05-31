---
title: "local robustness"
feed: show
date: 2023-05-31
alias: ""
---

__Local robustness__ is a property of [[Neural Network]]s that is concerned with not changing the network's classification or prediction around specific inputs.

For [[formal verification of neural networks|formal verification]], robustness to [[adversarial examples]] in an $$\mathcal{L}_{\infty}$$ ball around an input sample $$\mathbf{a}$$ with label $$y_a$$ can be encoded with a bounded input domain $$\mathcal{C} \triangleq \{\mathbf{x_0} \vert\ \lVert\mathbf{x_0} - \mathbf{a}\rVert_{\infty} \le \epsilon\}$$ and a property $$P(\mathbf{\hat{x}_n}) = \{\forall y,\ \hat{x}_{n[y_a]} > \hat{x}_{n[y]}\}$$.

In other words, changes in the input image that are smaller than some given value $$\epsilon$$ do not lead to a change in the network's output classification.

---

# Sources
- [[Branch and Bound for Piecewise Linear Neural Network Verification]]