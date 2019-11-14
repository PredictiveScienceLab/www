---
title: Causal inference on Bayesian graphical networks
summary: Learn potential causal structures with quantified uncertainties from observational data.
authors: [ebilionis]
tags:
- Facebook
- Past
- Causal inference
- Uncertainty quantification
- Decision-making under uncertainty
- Probabilistic graphical models
date: "2018-01-01T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption:
  focal_point: Smart

url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""
author: false
---

Imagine the scenario where a data science team needs to identify relationships among variables to decide which one is more important in to devote engineering efforts to change it and increase a quantity of interest.
This scenario applies, for example, to the case where one has observational data from the usage of an app and wishes to decide which app feature they should improve next.
Typically, the data scientists resort to probabilistic relationships (e.g., regressions).
These methods find correlations between intervention variables and quantities of interest and not causal relationships.
This is, of course, problematic because one should always base their decisions on knowledge of the causal mechanisms.
The objective of this project is to identify and quantify potential causal relationships from observational data. We use existing literature on causality to find potential causal relationships on observational data and turn this problem into decision making problem by incorporating uncertainty from the vague prior knowledge of the data science team.
The method is based on [Pearl's causality](https://projecteuclid.org/euclid.ssu/1255440554) but, instead of assuming a known causal graph, we put a prior on the space of causal graphs, condition it on the observational data, and derive one's posterior uncertainty over the space of causal graphs.
Using a Hastings-Metropolis algorithm, we sample potential causal graphs which are simultaneously compatible with one's prior knowledge and the data. We do so to find potential causal effects among variables.

**Collaborators:**

+ [Karthik Kannan](https://www.krannert.purdue.edu/faculty/kkarthik/)
+ [Abhishek Ray](https://www.linkedin.com/in/abray9/)
+ [Marios Papamichalis](https://www.researchgate.net/profile/Marios_Papamichalis)

**Funding Sponsor:**

+ [Facebook](https://about.fb.com/company-info/)
