# Delayed-Feedback Game Learning Experiments

Public code for the paper "Optimal Learning in Two-Player Zero-Sum Games under Delayed Feedback" in AISTATS2026.

This notebook reproduces the core experiments on two-player zero-sum games with delayed feedback, comparing the proposed method (`ProposedPlayer`) against the baseline (`FujimotoPlayer`).
It evaluates both social regret and individual regret under various delays $D$, learning rates $\eta$, and random seeds used for generating the payoff matrices.

---

## Environment Setup

This notebook uses `uv` for environment and dependency management.

### Setup Instructions

1. Install `uv` (see https://docs.astral.sh/uv/getting-started/installation/)
2. Run `uv sync` to install dependencies
3. When running the notebook, select the Python interpreter from `.venv` as the kernel

---

## References

Yuma Fujimoto, Abe Kenshi, and Kaito Ariu. Learning from delayed feedback in games via extra prediction. *In Advances in Neural Information Processing Systems*, volume 29, 2025. URL https://arxiv.org/abs/2509.22426.

---
