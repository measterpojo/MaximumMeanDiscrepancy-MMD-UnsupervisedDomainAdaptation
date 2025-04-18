# MaximumMeanDiscrepancy-MMD-UnsupervisedDomainAdaptation
Maximum Mean Discrepancy (MMD)/ Unsupervised Domain Adaptation with CIFAR10 as target domain and Pascal-voc-2012 as the source dataset


Introduction

Maximum Mean Discrepancy

Maximum Mean Discrepancy (MMD) is a kernel based statistical test used to determine whether two distributions are the same. It does this by measuring the distance between the means of the two distributions

MMD(X, Y) = ∥E[φ(X)] - E[φ(Y)]∥²

𝐸 [ 𝜑 (𝑋) ] : This is the expectation (mean) of the feature map 𝜑 applied to the samples from distribution 𝑋 . 𝐸 [ 𝜑 (𝑌) ] : This is the expectation (mean) of the feature map 𝜑 applied to the samples from distribution 𝑌. ∥...∥ ^ 2 : This represents the squared norm (distance) between the two mean feature vectors.

Why use MMD compared to other loss function for DA??

When it comes to domain adaptation (DA), MMD (Maximum Mean Discrepancy) has distinct advantages over Cross-Entropy Loss and Mean Squared Error (MSE) Loss due to its focus on aligning distributions rather than individual predictions. It directly addresses the issue of domain shift by aligning the distributions.
