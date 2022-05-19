# CuMF-SGD (Parallel computing)

I made this project to learn parallel computing. I experimented with different ways to parallelize matrix factorization (useful for recommender systems) using stochastic gradient descent, with inspiration from the CuMF-SGD paper (https://arxiv.org/abs/1610.05838).

I could achieve a speed-up of 5732x using CuPy on an RTX-3060 GPU, compared to a non-parallelized implementation on an i5-11400 CPU.
