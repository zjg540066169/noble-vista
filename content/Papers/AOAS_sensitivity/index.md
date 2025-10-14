---
title: "A flexible sensitivity analysis approach for unmeasured confounding with multiple treatments and a binary outcome with application to SEER-Medicare lung cancer data"
authors:
- Liangyuan Hu
- admin
- Chenyang Gu
- Jiayi Ji
- Michael Lopez
- Minal Kale
  
date: "2022-06-01T00:00:00Z"
publishDate: "2022-06-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "*The Annals of Applied Statistics*, 16(2), 1014-1037"
publication_short: ""

abstract: In the absence of a randomized experiment, a key assumption for drawing causal inference about treatment effects is the ignorable treatment assignment. Violations of the ignorability assumption may lead to biased treatment effect estimates. Sensitivity analysis helps gauge how causal conclusions will be altered in response to the potential magnitude of departure from the ignorability assumption. However, sensitivity analysis approaches for unmeasured confounding in the context of multiple treatments and binary outcomes are scarce. We propose a flexible Monte Carlo sensitivity analysis approach for causal inference in such settings. We first derive the general form of the bias introduced by unmeasured confounding, with emphasis on theoretical properties uniquely relevant to multiple treatments. We then propose methods to encode the impact of unmeasured confounding on potential outcomes and adjust the estimates of causal effects in which the presumed unmeasured confounding is removed. Our proposed methods embed nested multiple imputation within the Bayesian framework, which allow for seamless integration of the uncertainty about the values of the sensitivity parameters and the sampling variability as well as use of the Bayesian Additive Regression Trees for modeling flexibility. Expansive simulations validate our methods and gain insight into sensitivity analysis with multiple treatments. We use the SEER-Medicare data to demonstrate sensitivity analysis using three treatments for early stage nonsmall cell lung cancer. The methods developed in this work are readily available in the R package SAMTx.



tags:
- RCausal inference, ignorability assumption, observational data, Bayesian inference, nested multiple imputation.

featured: false
    
links:
- type: pdf
  url: https://projecteuclid.org/journals/annals-of-applied-statistics/volume-16/issue-2/A-flexible-sensitivity-analysis-approach-for-unmeasured-confounding-with-multiple/10.1214/21-AOAS1530.full
---
