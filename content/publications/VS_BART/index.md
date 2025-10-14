---
title: "Multi-level variable selection using a BART-enhanced mixed-effects framework"
authors:
- Keming Zhang
- Yaoyao Li
- admin
- Sijian Wang
- Bernadette Fausto
- Liangyuan Hu
  
date: "2025-09-30T00:00:00Z"
publishDate: "2025-09-30T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["preprint"]

# Publication name and optional abbreviated publication name.
publication: "Submitted"
publication_short: ""

abstract: Selecting important individual- and cluster-level predictors has become increasingly critical in healthcare research, where data often exhibit hierarchical structures due to collection from multiple clusters. Mixed-effects models, which account for within-cluster correlation and between-cluster heterogeneity, are a natural approach for multilevel variable selection. However, existing variable selection methods based on mixed-effects models typically rely on restrictive parametric assumptions, limiting their effectiveness in complex settings involving nonlinear relationships and interactions. Although nonparametric approaches have shown improved variable selection performance for non-clustered data, they remain underexplored for multilevel datasets. To address these limitations, we propose a flexible, fully Bayesian unified framework for simultaneous variable selection of both fixed and random effects. Our framework integrates the nonparametric flexibility of Bayesian Additive Regression Trees (BART) for fixed-effect predictor selection with a hierarchical Bayesian component that identifies random-effect predictors via covariance decomposition and permutation strategies. To address scenarios common in multilevel data, where cluster-level covariates are constant within clusters and can induce near-collinearity and instability in selection, we further propose a computationally efficient two-step procedure. This method disentangles the contributions of individual- and cluster-level predictors, thereby mitigating collinearity and improving stability in variable selection. Comprehensive simulation studies demonstrate the effectiveness and robustness of our proposed methods across diverse scenarios. We further illustrate the practical utility of these approaches by applying them to a multilevel Alzheimer's disease dataset.

tags:
- Bayesian machine learning, Metropolis importance, Dirichlet distribution, Spike and slab prior, Permutation-based, Near-collinearity.

featured: false
---
