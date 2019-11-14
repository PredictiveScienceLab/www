---
title: Using data science to discover materials with extreme properties.
summary: Discovery of high-temperature, oxidation resistant, complex, concentrated alloys via data science driven multi-resolution experiments and simulations.
authors: ["sharmila", "ebilionis"]
tags:
- NSF
- Current
- Uncertainty quantification
- Physics-informed machine learning
- Sequential design of experiments
- Materials design
- Deep ;earning
date: "2019-08-15T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption: Schematic description of the approach.
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

Metallic alloys capable of maintaining high strength at temperatures over 1,000&deg;C, while exhibiting high
oxidation resistance are a key technology in aerospace and energy applications. Current state-of-art Ni-
based superalloys exhibit excellent resistance to oxidation, but their application is limited by their melting
temperature of approximately 1,300&deg;C. Quite interestingly, in recent years, refractory complex
concentrated alloys (RCCAs) emerged as a possible alternative with the potential to achieve higher
operation temperatures. While multi-component RCCAs (also known as high entropy alloys) with high-
temperature strength surpassing Ni superalloys have been developed, their oxidation resistance is far from
ideal. We hypothesize that given the high-dimensional and mostly unexplored compositional and
processing space of RCCAs together with the existence of closed packed oxides of the metals of interest,
the oxidation resistance of RCCAs can be significantly improved without negatively affecting strength and
processability. Motivated by this opportunity, the goal of this project is to discover RCCAs with
unsurpassed combination of high temperature strength and oxidation resistance.

{{< figure src="/img/nsf-dmref-dnn.png" caption="An abstract representation of the deep neural network that learns correlations between sources of multiple fidelities." >}}

The design and optimization of RCCAs with the combination of properties sought after is a daunting task due to the extremely large number of potential alloys, and because the oxidation behavior of these complex alloys is not fully understood. Adding oxidation testing variables (temperature, partial pressure of O) to the compositional ones, the space to be explored is 17 dimensional, clearly out of reach to brute force approaches given the time and cost involved in high-temperature oxidation experiments. Physics-based modeling could, in principle, help reduce the number of experimental trials. However, our ability to predict oxidation in complex alloys is limited. Computationally expedient approaches lack accuracy or cannot be applied to multi-component alloys and a complete first principles exploration of oxide formation in an RCCA would require the full resources and time of this project for a single alloy. Fortunately, recent breakthroughs by our team and others indicate that achieving the ambitious goal of this project is possible via an iterative approach that combines
multi-fidelity and multi-cost experiments and physics-based modeling with a machine learning for accelerated materials discovery (ML- AMD) framework. ML-AMD will use sequential learning with deep neural networks (DNNs) to develop models based on disparate sources of information and accounting for uncertainties and identify simulations and experiments to carry out in order to maximize information gain towards our design goal.

**Collaborators:**

+ [Alejandro Strachan (PI)](https://nanohub.org/groups/strachangroup/alestrachan)
+ [Michael Titus (Co-PI)](https://engineering.purdue.edu/MSE/people/ptProfile?resource_id=144082)
+ [Kenneth Sandhage (Co-PI)](https://engineering.purdue.edu/MSE/people/ptProfile?resource_id=126421)

**Funding:**

+ [NSF](https://www.nsf.gov/awardsearch/showAward?AWD_ID=1922316&HistoricalAwards=false)
