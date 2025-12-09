# Numerical Experiments for the Jacobi-Proximal ADMM

This repository contains the code for the numerical experiments presented in the following paper, which analyzes the **Jacobi-Proximal Alternating Direction Method of Multipliers (ADMM)**.

## Paper Information

**Title:** *A linear convergence result for the Jacobi-Proximal Alternating Direction Method of Multipliers*

**Authors:** Hyelin Choi and Woocheol Choi

**Preprint:** [https://arxiv.org/abs/2503.18601]

**Status:** Under review at *Computational Optimization and Applications*

## Numerical Experiments

The Jacobi-Proximal ADMM is tested on the following problems. The convergence behavior is analyzed by varying the key algorithmic parameters, $\gamma$ (damping parameter) and $\rho$ (penalty parameter).

| Filename | Experiment Title | Parameter |
| :--- | :--- | :--- |
| **`ex1.ipynb`** | Linear Constrained Quadratic Program (LCQP) Model | **Damping Parameter ($\gamma$):** $`\gamma \in \{0.1, 0.5, 1.5, 1.9\}`$.<br>**Penalty Parameter ($\rho$):** $`\rho \in \{0.03, 1, 5, 10\}$ for $N=3`$; $`\rho \in \{10^{-5}, 0.1, 5, 10\}`$ for $N=10$.|
| **`ex2.ipynb`** | Optimal Resource Allocation Problem (ORAP) | **Damping Parameter ($\gamma$):** $`\gamma \in \{0.1, 0.5, 1.5, 1.9\}`$.<br>**Penalty Parameter ($\rho$):** $`\rho \in \{0.03, 1, 5, 10\}`$.|






