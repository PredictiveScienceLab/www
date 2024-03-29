---
title: "Deep UQ: Learning deep neural network surrogate models for high dimensional uncertainty quantification"
date: 2018-12-01
publishDate: 2019-11-12T12:56:14.855461Z
authors: ["Rohit K. Tripathy", "Ilias Bilionis"]
publication_types: ["2"]
abstract: "State-of-the-art computer codes for simulating real physical systems are often characterized by vast number of input parameters. Performing uncertainty quantification (UQ) tasks with Monte Carlo (MC) methods is almost always infeasible because of the need to perform hundreds of thousands or even millions of forward model evaluations in order to obtain convergent statistics. One, thus, tries to construct a cheap-to-evaluate surrogate model to replace the forward model solver. For systems with large numbers of input parameters, one has to address the curse of dimensionality through suitable dimensionality reduction techniques. A popular class of dimensionality reduction methods are those that attempt to recover a low-dimensional representation of the high-dimensional feature space. However, such methods often tend to overestimate the intrinsic dimensionality of the input feature space. In this work, we demonstrate the use of deep neural networks (DNN) to construct surrogate models for numerical simulators. We parameterize the structure of the DNN in a manner that lends the DNN surrogate the interpretation of recovering a low-dimensional nonlinear manifold. The model response is a parameterized nonlinear function of the low-dimensional projections of the input. We think of this low-dimensional manifold as a nonlinear generalization of the notion of the active subspace. Our approach is demonstrated with a problem on uncertainty propagation in a stochastic elliptic partial differential equation (SPDE) with uncertain diffusion coefficient. We deviate from traditional formulations of the SPDE problem by lifting the assumption of fixed lengthscales of the uncertain diffusion field. Instead we attempt to solve a more challenging problem of learning a map between an arbitrary snapshot of the diffusion field and the response."
featured: false
publication: "*Journal of Computational Physics*"
tags: ["Uncertainty quantification", "Deep Neural Networks", "Dimensionality reduction", "Stochastic elliptic PDE"]
url_pdf: "http://www.sciencedirect.com/science/article/pii/S0021999118305655"
doi: "10.1016/j.jcp.2018.08.036"
projects: ["darpa-pilgrims"]
---
