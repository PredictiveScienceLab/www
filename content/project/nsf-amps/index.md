---
title: Efficient Algorithms for Ultra-fast Detection of Power System Contingencies in the Transient Regime.
summary: Ultra-fast detection of faults in the power grid.
tags:
- NSF
- Current
- Uncertainty quantification
- Fault detection and diagnosis
date: "2018-08-15T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption: Image from [North American SynchoPhasor Initiative](https://naspi.org/)
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

The stability of the electric power system is of the utmost importance for its reliable operation. This work focuses on the impact of large disturbances, such as the loss of a transmission line due to a short-circuit, or the sudden disconnection of a thermal generating unit due to an unpredictable malfunction. When such faults occur, the system undergoes a transient event of highly nonlinear nature. The ongoing large-scale integration of renewable energy resources in the grid challenges conventional transient stability analysis, and reduces the 'inertia' of the system. At the same time, there is a proliferation of phasor measurement units (PMUs) on the grid. These sensors provide accurate, high-frequency information about voltage, current, and frequency at various locations around the system, and are instrumental in increasing our system-level situation awareness. Nevertheless, the transformation of the incoming data to actionable information is still an open research problem. In the context of transient regimes, it is important to establish as soon as possible, i.e., within a few electrical cycles, what has gone wrong, in order to predict the evolution of the system dynamics over the period of time following the fault. Such 'ultra-fast' detection is critical, since it may allow appropriate actions to be taken by a wide-area monitoring and control system that can actuate various assets around the grid, such as flexible ac transmission system (FACTS) devices or even the converters of renewable resources.

{{< figure src="/img/nsf-amps-approach.png" title="Overview of the approach.">}}

The main objective of this work is to develop computationally scalable, yet statistically efficient, real-time algorithms in order to detect and identify contingencies in the early stages of the transient regime of the power system based on PMU outputs. The validity and efficacy of these algorithms will be based on a stochastic model for the power system during the transient stability regime following a contingency. This is a very challenging problem that cannot be addressed with existing uncertainty propagation methodologies, because of the high-dimensionality and the computational complexity of the power grid dynamical system. A key component is the reformulation of the uncertainty propagation problem which overcomes the curse of dimensionality, enables the fast re-estimation of the statistics as the power system operating point changes, and allows for the adaptive selection of power system simulations. This work will rely on combination of diverse techniques, such as uncertainty quantification, power grid modeling, and sequential detection.

**Collaborators:**

+ [Dionysios Aliprantis (Co-PI)](https://engineering.purdue.edu/~dionysis/)
+ [Georgios Fellouris (Co-PI)](https://stat.illinois.edu/directory/profile/fellouri)

**Funding Sponsor:**

+ [NSF](https://www.nsf.gov/awardsearch/showAward?AWD_ID=1736437&HistoricalAwards=false)
