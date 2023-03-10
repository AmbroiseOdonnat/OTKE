# Optimal Transport Kernel Embedding for Sets (OTKE)
Report and experiments done to study [A Trainable Optimal Transport Embedding for Feature Aggregation and its Relationship to Attention](https://openreview.net/pdf?id=ZK6vTvb84s) for the course of Computational Optimal Transport, Master MVA at ENS Paris-Saclay 2022-2023.

## Contributions
Our contributions are three folds. In this paper, (i) we evaluate the quality of the Wasserstein distance approximation obtained via the proposed embedding. We show on 1D and 2D Gaussian distributions that the approximation error decreases with the number of points in reference. (ii) We propose an approximation of the p-Wasserstein distance and show that our 1-Wasserstein distance approximation can be used as a loss function in Wasserstein GAN. (iii) Finally, we display the benefits and robustness of the optimal transport kernel embedding on a logistic classification task with 2D Gaussian distributions.

## Report
Report with our contributions to find [here](https://github.com/AmbroiseOdonnat/OTKE/blob/main/OTKE_report.pdf).

## Code
Python implementation of our experiments to find [here](https://github.com/AmbroiseOdonnat/OTKE/blob/main/main.ipynb).


