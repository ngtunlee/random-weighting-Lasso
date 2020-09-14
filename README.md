We consider a general-purpose approximation approach to Bayesian inference in which repeated optimization of a randomized objective function provides surrogate samples from the joint posterior distribution. In the context of LASSO regression, we repeatedly assign independently-drawn random weights to terms in the objective function, and optimize to obtain the surrogate samples. 

[Newton et. al. (2020)](https://onlinelibrary.wiley.com/doi/epdf/10.1002/cjs.11570) have shown promising numerical properties of this approach. Here, we establish the asymptotic properties of this method under different regularization parameters: [arXiv:2002.02629](https://arxiv.org/abs/2002.02629).  

This repo also contains the [slides](https://github.com/ngtunlee/random-weighting-Lasso/blob/master/IFDS_May2019.pdf) of my talk about this topic during one of the weekly seminars of UW Madison IFDS (Institute for Foundations of Data Science). 
