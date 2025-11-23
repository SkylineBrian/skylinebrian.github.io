---
layout: post
title: "Bayesian inference using the proximal mapping: Uncertainty quantification under varying dimensionality"
excerpt: "New article first published online: Journal of the American Statistical Associat..."
author: "thatdrwho"
date: 2023-07-10
description: "New article first published online: Journal of the American Statistical Association ABSTRACT: In statistical applications, it is common to encounter parameters..."
image: ""
publishDate: 2023-07-10
post_type_custom: publication
tags:
  - GeoNAVI
categories: [ Pubs ]
URL: "/2023/07/10/bayesian-inference-using-the-proximal-mapping-uncertainty-quantification-under-varying-dimensionality/"
---

<div style="clear: both"></div>
New article first published online: <a href="https://www.tandfonline.com/doi/full/10.1080/01621459.2023.2220170" target="_blank" rel="noopener">Journal of the American Statistical Association</a>

<strong>ABSTRACT:</strong> In statistical applications, it is common to encounter parameters supported on a varying or unknown dimensional space. Examples include the fused lasso regression, the matrix recovery under an unknown low rank, etc. Despite the ease of obtaining a point estimate via optimization, it is much more challenging to quantify their uncertainty. In the Bayesian framework, a major difficulty is that if assigning the prior associated with a p-dimensional measure, then there is zero posterior probability on any lower-dimensional subset with dimension d < p. To avoid this caveat, one needs to choose another dimension-selection prior on d, which often involves a highly combinatorial problem. To significantly reduce the modeling burden, we propose a new generative process for the prior: starting from a continuous random variable such as multivariate Gaussian, we transform it into a varying-dimensional space using the proximal mapping. This leads to a large class of new Bayesian models that can directly exploit the popular frequentist regularizations and their algorithms, such as the nuclear norm penalty and the alternating direction method of multipliers, while providing a principled and probabilistic uncertainty estimation. We show that this framework is well justified in the geometric measure theory, and enjoys a convenient posterior computation via the standard Hamiltonian Monte Carlo. We demonstrate its use in the analysis of the dynamic flow network data. Supplementary materials for this article are available online.