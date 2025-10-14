---
title: "Nonparametric Bayesian Additive Regression Trees for Prediction and Missing Data Imputation in Longitudinal Studies"
authors:
- admin
- Liangyuan Hu
  
date: "2025-09-30T00:00:00Z"
publishDate: "2025-09-30T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["preprint"]

# Publication name and optional abbreviated publication name.
publication: "Under preparation"
publication_short: ""

abstract: The missing data issue in longitudinal covariates and outcomes poses substantial challenges. Traditional multiple imputation methods, such as MICE and joint models, are widely used under the missing at random assumption but often suffer from uncongeniality, increased complexity with numerous covariates, and bias due to parametric model misspecification. To address these limitations, we propose a flexible Bayesian nonparametric sequential imputation framework tailored for longitudinal data. We first develop a Bayesian ensemble-tree mixed-effects model BMTrees, and its variants, which leverage nonparametric priors to capture complex, non-linear relationships over time and handle non-normal random effects and errors. We then adapt BMTrees to the sequential imputation framework, effectively modeling relationships between observed and missing variables. Simulation studies demonstrate that BMTrees outperforms established ensemble-tree methods, including mixedBART and mixedRF, in both prediction and imputation tasks, particularly in challenging scenarios with non-normal data structures. Through a case study, we demonstrate the use of our sequential imputation method combined with longitudinal causal inference techniques to evaluate the comparative effectiveness of antihypertensive treatment initiation thresholds for reducing long-term systolic blood pressure.

tags:
- longitudinal missing data, Bayesian nonparametric methods, sequential imputation, mixed-effects models, multiple imputation.

featured: false
---
