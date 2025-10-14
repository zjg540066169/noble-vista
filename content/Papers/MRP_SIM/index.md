---
title: "Improving Survey Inference Using Administrative Records Without Releasing Individual-Level Continuous Data"
authors:
- Sharifa Z. Williams
- admin
- Yutao Liu
- Yajuan Si
- Sandro Galea
- Qixuan Chen
  
date: "2024-11-18T00:00:00Z"
publishDate: "2024-11-18T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "*Statistics in Medicine*, 43(30), 5803-5813"
publication_short: ""

abstract: Probability surveys are challenged by increasing nonresponse rates, resulting in biased statistical inference. Auxiliary information about populations can be used to reduce bias in estimation. Often continuous auxiliary variables in administrative records are first discretized before releasing to the public to avoid confidentiality breaches. This may weaken the utility of the administrative records in improving survey estimates, particularly when there is a strong relationship between continuous auxiliary information and the survey outcome. In this paper, we propose a two-step strategy, where the confidential continuous auxiliary data in the population are first utilized to estimate the response propensity score of the survey sample by statistical agencies, which is then included in a modified population data for data users. In the second step, data users who do not have access to confidential continuous auxiliary data conduct predictive survey inference by including discretized continuous variables and the propensity score as predictors using splines in a Bayesian model. We show by simulation that the proposed method performs well, yielding more efficient estimates of population means with 95% credible intervals providing better coverage than alternative approaches. We illustrate the proposed method using the Ohio Army National Guard Mental Health Initiative (OHARNG-MHI). The methods developed in this work are readily available in the R package AuxSurvey.

tags:
- Bayesian predictive inference, continuous auxiliary variables, generalized additive model, inclusion propensity, poststratification, Rstan

featured: false
    
links:
- type: pdf
  url: https://onlinelibrary.wiley.com/doi/10.1002/sim.10270
---
