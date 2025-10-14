
---
title: "Bayesian MI-LASSO for Variable Selection on Multiply-Imputed Data"
authors:
- admin
- Sijian Wang
- Qixuan Chen
  
date: "2025-08-06T00:00:00Z"
publishDate: "2025-08-06T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["preprint"]

# Publication name and optional abbreviated publication name.
publication: "Bayesian MI-LASSO for Variable Selection on Multiply-Imputed Data"
publication_short: ""

abstract: Multiple imputation is widely used for handling missing data in real-world applications. For variable selection on multiply-imputed datasets, however, if selection is performed on each imputed dataset separately, it can result in different sets of selected variables across datasets. MI-LASSO, one of the most commonly used approaches to this problem, regards the same variable across all separate imputed datasets as a group variable and exploits the group LASSO to yield a consistent variable selection across all the multiply-imputed datasets. In this paper, we extend MI-LASSO to a Bayesian framework and propose four Bayesian MI-LASSO models for variable selection on multiply-imputed data, including three shrinkage prior-based and one Spike-Slab prior-based methods. To further support robust variable selection, we develop a four-step projection predictive variable selection procedure that avoids ad hoc thresholding and facilitates valid post-selection inference. Simulation studies showed that the Bayesian MI-LASSO outperformed MI-LASSO and other alternative approaches, achieving higher specificity and lower mean squared error across a range of settings. We further demonstrated these methods via a case study using a multiply-imputed dataset from the University of Michigan Dioxin Exposure Study. The R package BMIselect is available on CRAN.


tags:
- Bayesian models, Group LASSO, Multiple imputation, Projection predictive variable selection.

featured: false
    
links:
  - type: pdf
    url: [http://arxiv.org/pdf/1512.04133v1](https://arxiv.org/pdf/2211.00114v2)
  - type: preprint
    provider: arxiv
    id: 2211.00114v2
  - type: code
    url: https://cran.r-project.org/web/packages/BMIselect/index.html


# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
- internal-project

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---

This work is driven by the results in my [previous paper](/publications/conference-paper/) on LLMs.

> [!NOTE]
> Create your slides in Markdown - click the *Slides* button to check out the example.

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/).
