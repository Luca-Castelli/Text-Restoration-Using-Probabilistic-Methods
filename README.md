# Text-Restoration-Using-Probabilistic-Methods

### Abstract
This report combines the results of Geman and Geman’s Stochastic Relaxation, Gibbs Distributions, and the Bayesian Restoration of Images (1984) and Mumford, Wu, and Zhu’s
Filters, Random Fields and Maximum Entropy (1998) to restore images. Images are modelled as Markov random fields (MRF) and the equivalence between Markov random fields
and Gibbs random fields is exploited. An adequate energy function is defined. Given an
image with white additive noise, the posterior probability is an MRF with respect to a neighbourhood structure. By introducing simulated annealing the problem of image restoration
becomes a maximum a posteriori (MAP) estimation problem of an ideal image given a
noisy image. The performance of the restoration procedure is improved by utilizing the
FRAME algorithm to learn suitable image priors. The FRAME methodology makes use of
the maximum entropy principle, filters and Markov random fields. Filters are selected to
capture characteristics of images, histograms are generated from the filtered images, and a
gradient descent procedure is followed while making use of the Gibbs Sampler.
