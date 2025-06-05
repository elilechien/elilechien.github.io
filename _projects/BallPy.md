---
title: "BallPy: Bug Analyzing Local LLM for Python"
excerpt: "Reducing the size of language models by learning which weights to prune while maintaining high performance."
date: 2025-06-04
tags:
  - Machine Learning
  - Reinforcement Learning
  - LLMs
  - DPO
---

## Overview

This project focuses on applying reinforcement learning (RL) to **prune large language models (LLMs)** efficiently, balancing model size and performance. The approach uses PPO (Proximal Policy Optimization) to select weights to zero out in transformer layers, particularly targeting the key, value, and feed-forward layers.

### Goals
- Reduce model size while maintaining log-likelihood performance.
- Improve inference speed and memory footprint on GPUs.
- Validate pruning strategies with real-world language generation tasks.

## Methodology

1. **Model**: LLaMA 1B.
2. **Target Layers**: Key, Value, and Feed-Forward Network (FFN).
3. **Pruning Approach**: Structured pruning via RL.
4. **Evaluation**: Compare log-likelihood, generation quality, and speed.

## Results

- Achieved a **10% reduction in model parameters**
## Next Steps

- Explore hybrid pruning strategies combining RL with magnitude-based pruning.
- Integrate model quantization for even greater efficiency.

## Repository

[Check out the code on GitHub!](https://github.com/elilechien/llm-pruning)

---

If you want, I can also help you design a project layout or add images, charts, or code snippets. Let me know! 🚀
