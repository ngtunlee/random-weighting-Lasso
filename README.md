We consider a general-purpose approximation approach to Bayesian inference in which repeated optimization of a randomized objective function provides surrogate samples from the joint posterior distribution. In the context of LASSO regression, we repeatedly assign independently-drawn random weights to terms in the objective function, and optimize to obtain the surrogate samples. 

[Newton et. al. (2020)](https://onlinelibrary.wiley.com/doi/epdf/10.1002/cjs.11570) have shown promising numerical properties of this approach. Here on [arXiv:2002.02629](https://arxiv.org/abs/2002.02629), we show that existing approaches  have conditional model selection consistency and conditional asymptotic normality at different growth rates of $\lambda_n$ as $n \to \infty$. We  propose an extension to the available random-weighting methods and establish that the resulting samples attain conditional sparse normality and conditional consistency in a growing-dimension setting. We find that random-weighting has both approximate-Bayesian and sampling-theory interpretations.    

This repo also contains the [slides](https://github.com/ngtunlee/random-weighting-Lasso/blob/master/IFDS_May2019.pdf) of my talk about this topic during one of the weekly seminars of UW Madison IFDS (Institute for Foundations of Data Science). 
