# AdaMod-tf

This is a Tensorflow 2.0 version of the AdaMod Optimizer from the paper 
[An Adaptive and Momental Bound Method for Stochastic Learning](https://arxiv.org/abs/1910.12249v1)

A beta_3 between 0.999 and 0.9999 is recommended, I put the default at 0.9995.
Larger beta_3s take longer to converge but converge to a better solution.