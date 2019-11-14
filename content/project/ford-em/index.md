---
title: Design of electric machines with manufacturing uncertainties
summary: Development of computational tools for electric machine design including manufacturing uncertainties.
authors: ["andres", "abhijit", "ebilionis"]
tags:
- Ford
- Illinois
- Current
- Uncertainty quantification
- Gaussian process
- Principal component analysis
date: "2018-08-15T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption: Cross-section of one pole of a permanent magnet motor.
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

---

The manufacturing process of electric machines (EMs) can lead to deviations between expected and observed performance.
One cause of these deviations is the inherent input space uncertainty of the EM model employed during the design stage.
Understanding how this uncertainty affects the performance of EMs is imperative to develop robust design techniques.
To investigate these effects, in this work, a permanent magnet synchronous machine (PMSM) is selected as the central case study.
The objective of this project is to set forth a computationally efficient methodology to quantitatively characterize the effects and relevance of the input space uncertainty on multiple quantities of interest of a PMSM.

{{< figure src="/img/ford-results.png" caption="Uncertainty propagation (left) and sensitivity analysis (right) of the average torque (top) and the torque ripple (bottom)." >}}

**Collaborators:**

+ [Dionysios Aliprantis (Co-PI)](https://engineering.purdue.edu/~dionysis/)

**Funding:**

+ [Ford](https://www.ford.com/)
+ [University of Illinois Urbana-Champaign](https://illinois.edu/)
