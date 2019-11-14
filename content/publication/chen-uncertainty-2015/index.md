---
title: "Uncertainty propagation using infinite mixture of Gaussian processes and variational Bayesian inference"
date: 2015-03-01
publishDate: 2019-11-12T12:56:14.848386Z
authors: ["Peng Chen", "Nicholas Zabaras", "Ilias Bilionis"]
publication_types: ["2"]
abstract: "Uncertainty propagation in flow through porous media problems is a challenging problem. This is due to the high-dimensionality of the random property fields, e.g. permeability and porosity, as well as the computational complexity of the models that are involved. The usual approach is to construct a surrogate response surface and then use it instead of the expensive model to carry out the uncertainty propagation task. However, the construction of the surrogate surface is hampered by various aspects such as the limited number of model evaluations that one can afford, the curse of dimensionality, multi-variate responses with non-trivial correlations, potential localized features of the response and/or discontinuities. In this work, we extend upon the concept of the Multi-output Gaussian Process (MGP) to effectively deal with all of these difficulties simultaneously. This non-trivial extension involves an infinite mixture of MGP's that is trained using variational Bayesian inference. Prior to observing any data, a Dirichlet process is used to generate the components of the MGP mixture. The Bayesian nature of the model allows for the quantification of the uncertainties due to the limited number of simulations, i.e., we can derive error bars for the statistics of interest. The automatic detection of the mixture components by the variational inference algorithm is able to capture discontinuities and localized features without adhering to ad hoc constructions. Finally, correlations between the components of multi-variate responses are captured by the underlying MGP model in a natural way."
featured: false
publication: "*Journal of Computational Physics*"
tags: ["Dirichlet process", "Infinite mixture of Gaussian processes", "Multi-output Gaussian process", "Nonparametric variational inference", "Reservoir simulation", "Uncertainty quantification", "Variational inference"]
url_pdf: "http://www.sciencedirect.com/science/article/pii/S0021999114008456"
doi: "10.1016/j.jcp.2014.12.028"
---

