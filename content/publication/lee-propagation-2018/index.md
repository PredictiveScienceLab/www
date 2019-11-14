---
title: "Propagation of material behavior uncertainty in a nonlinear finite element model of reconstructive surgery"
date: 2018-12-01
publishDate: 2019-11-12T12:56:14.858603Z
authors: ["Taeksang Lee", "Sergey Y. Turin", "Arun K. Gosain", "Ilias Bilionis", "Adrian Buganza Tepole"]
publication_types: ["2"]
abstract: "Excessive mechanical stress following surgery can lead to delayed healing, hypertrophic scars, and even skin necrosis. Measuring stress directly in the operating room over large skin areas is not feasible, and nonlinear finite element simulations have become an appealing alternative to predict stress contours on arbitrary geometries. However, this approach has been limited to generic cases, when in reality each patient geometry and procedure are unique, and material properties change from one person to another. In this manuscript, we use multi-view stereo to capture the patient-specific geometry of a 7-year-old female undergoing cranioplasty and complex tissue rearrangement. The geometry is used to setup a nonlinear finite element simulation of the reconstructive procedure. A key contribution of this work is incorporation of material behavior uncertainty. The finite element simulation is computationally expensive, and it is not suitable for uncertainty propagation which would require many such simulations. Instead, we run only a few expensive simulations in order to build a surrogate model by Gaussian process regression of the principal components of the stress fields computed with these few samples. The inexpensive surrogate is then used to compute the statistics of the stress distribution in this patient-specific scenario."
featured: false
publication: "*Biomechanics and Modeling in Mechanobiology*"
tags: ["Uncertainty propagation", "Gaussian process regression", "Multi-view stereo", "Nonlinear finite elements", "Patient-specific simulation", "Principal component analysis"]
url_pdf: "https://doi.org/10.1007/s10237-018-1061-4"
doi: "10.1007/s10237-018-1061-4"
---
