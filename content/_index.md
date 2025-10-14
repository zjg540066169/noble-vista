
---
# Leave the homepage title empty to use the site title
title: 'Jungang Zou'
date: 2025-10-14
type: landing

design:
  # Default section spacing
  spacing: '6rem'

sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      text: ''
      # Show a call-to-action button under your biography? (optional)
      button:
        text: Download CV
        url: uploads/resume.pdf
      headings:
        about: ''
        education: ''
        interests: ''
    design:
      # Apply a gradient background
      css_class: hbx-bg-gradient
      # Avatar customization
      avatar:
        size: medium # Options: small (150px), medium (200px, default), large (320px), xl (400px), xxl (500px)
        shape: circle # Options: circle (default), square, rounded
  - block: collection
    content:
      title: publications
      text: ''
      filters:
        folders:
          - publications
        exclude_featured: true
    design:
      view: citation
  - block: collection
    content:
      title: preprints
      text: ''
      filters:
        folders:
          - preprints
        exclude_featured: true
    design:
      view: citation
  - block: markdown
    id: software
    content:
      title: "R & Python Packages"
      text: |
        - **[SBMTrees](https://cran.r-project.org/web/packages/SBMTrees/index.html)** — Sequential Imputation with Bayesian Trees Mixed-Effects Models for Longitudinal Data [CRAN](https://cran.r-project.org/web/packages/SBMTrees/index.html) • [GitHub](https://github.com/zjg540066169/SBMTrees)
        - **[AuxSurvey](https://cran.r-project.org/web/packages/AuxSurvey/index.html)** — Survey Analysis with Auxiliary Discretized Variables [CRAN](https://cran.r-project.org/web/packages/AuxSurvey/index.html) • [GitHub](https://github.com/zjg540066169/AuxSurvey)
        - **[SAMTx](https://cran.r-project.org/web/packages/SAMTx/index.html)** — Sensitivity Assessment to Unmeasured Confounding with Multiple Treatments [CRAN](https://cran.r-project.org/web/packages/SAMTx/index.html)
        - **[BMIselect](https://cran.r-project.org/web/packages/BMIselect/index.html)** — Bayesian MI-LASSO Models for Variable Selection on Multiply-Imputed Data [CRAN](https://cran.r-project.org/web/packages/BMIselect/index.html) • [GitHub](https://github.com/zjg540066169/BMIselect)
        - **[TMOGA](https://pypi.org/project/tmoga/)** — A Multi-Objective Genetic Algorithm for Dynamic Community Detection Problem [PyPI](https://pypi.org/project/tmoga/) • [GitHub](https://github.com/zjg540066169/TMOGA)
  - block: collection
    id: talks
    content:
      title: Talks
      filters:
        folders:
          - events
    design:
      view: card
---
