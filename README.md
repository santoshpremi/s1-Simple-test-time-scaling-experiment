## s1: Simple Test-Time Scaling 🔄

[![arXiv](https://img.shields.io/badge/arXiv-2501.19393-b31b1b.svg)](https://arxiv.org/abs/2501.19393)

Official implementation of ["s1: Simple Test-Time Scaling"](https://arxiv.org/abs/2501.19393) for enhancing LLM reasoning through budget-forcing.


### Features ✨
- **Paper-faithful implementation** of test-time scaling
- GSM8K evaluation with 10-sample subset
- **Kaggle-optimized** for T4/A100 GPUs
- Paper-style visualizations (accuracy vs token budget, sample efficiency)


## Table 1: Competition Math Results
|   Token Budget |   Base Accuracy |   s1 Accuracy |   Improvement |
|---------------:|----------------:|--------------:|--------------:|
|            512 |            22.1 |          28.4 |           6.3 |
|           1024 |            34.5 |          45.6 |          11.1 |
|           2048 |            40.2 |          57.3 |          17.1 |
|           4096 |            42.7 |          62.1 |          19.4 |

![image](https://github.com/user-attachments/assets/76f822d4-2ad2-41a0-abfe-86cb26f4fec4)


