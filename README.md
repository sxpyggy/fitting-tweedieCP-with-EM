# Fitting Tweedie's compound Poisson model to pure premium with the EM algorithm

Abstract: We consider the situation when the number of claims is unavailable, and a Tweedie’s
compound Poisson model is fitted to the observed pure premium. Currently, there are two
different models based on the Tweedie distribution: a single generalized linear model (GLM)
for mean and a double generalized linear model (DGLM) for both mean and dispersion.
Although the DGLM approach facilitates the heterogeneous dispersion, its soundness relies
on the accuracy of the saddlepoint approximation, which is poor when the proportion of zero
claims is large. For both models, the power variance parameter is estimated by considering
the profile likelihood, which is computationally expensive. We propose a new approach to fit
the Tweedie model with the EM algorithm, which is equivalent to an iteratively re-weighted
Poisson-gamma model on an augmented data set. The proposed approach addresses the
heterogeneous dispersion without needing the saddlepoint approximation, and the power
variance parameter is estimated during the model fitting. Numerical examples show that
our proposed approach is superior to the two competing models.

Keywords: Tweedie’s compound Poisson model; Tweedie distribution; Exponential dispersion family; The EM algorithm; Generalized linear model.
