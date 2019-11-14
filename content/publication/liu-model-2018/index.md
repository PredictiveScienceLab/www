---
title: "Model predictive control under forecast uncertainty for optimal operation of buildings with integrated solar systems"
date: 2018-09-01
publishDate: 2019-11-12T12:56:14.869564Z
authors: ["Xiaoqi Liu", "Parth Paritosh", "Nimish M. Awalgaonkar", "Ilias Bilionis", "Panagiota Karava"]
publication_types: ["2"]
abstract: "In this paper, we explore intelligent operation strategies, based on stochastic model predictive control (SMPC), for optimal utilization of solar energy in buildings with integrated solar systems. Our approach takes into account the uncertainty in solar irradiance forecast over a prediction horizon, using a new probabilistic time series autoregressive model, calibrated on the sky-cover forecast from a weather service provider. In the optimal control formulation, we model the effect of solar irradiance as non-Gaussian stochastic disturbance affecting the cost and constraints, and the nonconvex cost function is an expectation over the stochastic process. To solve this complex optimization problem, we introduce a new approximate dynamic programming methodology that represents the optimal cost-to-go functions using Gaussian process regression, and achieves good solution quality. In the final step, we use an emulator that couples physical system models in TRNSYS with the SMPC controller developed using Python and MATLAB to evaluate the closed-loop operation of a building-integrated system with a solar-assisted heat pump coupled with radiant floor heating. For the system and climate under consideration, the SMPC saves up to 44% of the electricity consumption for heating in a winter month, compared to a baseline well-tuned rule-based controller, and it is robust, imposing less uncertainty on thermal comfort violation."
featured: false
publication: "*Solar Energy*"
tags: ["Approximate dynamic programming", "Autoregressive model", "Building-integrated solar energy systems", "Forecast uncertainty"]
url_pdf: "http://www.sciencedirect.com/science/article/pii/S0038092X18305899"
doi: "10.1016/j.solener.2018.06.038"
projects: ["nsf-cybersees"]
---
