---
title: "Research"
type: landing

sections:
  - block: collection
    id: papers
    content:
      title: "Papers"
      filters:
        folders: ["Papers"]        # or "papers" if your folder is lower-case
        kinds: ["page"]
    design:
      view: card
      columns: 2

  - block: collection
    id: publications
    content:
      title: "Publications"
      filters:
        folders: ["publications"]
        kinds: ["page"]
    design:
      view: card
      columns: 2

  - block: markdown
    id: software
    content:
      title: "Software"
      text: |
        See all packages on the **Software** page.
        - [SBMTrees](/softwares/sbmtrees/)
        - [AuxSurvey](/softwares/auxsurvey/)
        - [BMIselect](/softwares/bmiselect/)
---
