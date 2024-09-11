---
layout: default
title: Home
nav_order: 1
description: "CoReX: Context-Aware Refinement-Based Slicing for Debugging Regression Failures"
permalink: /
---

### CoReX: Context-Aware Refinement-Based Slicing for Debugging Regression Failures

---

Troubleshooting regression failures is one of the most frequent yet time-consuming development tasks. To help developers with this task, numerous approaches aim to automatically identify a subset of program statements relevant to the failure, minimizing the amount of code developers need to inspect. The most prominent of these approaches are based on program slicing, as slicing makes it possible to maintain dependencies and flow of information between the identified statements. 

We observe that existing slicing-based approaches for the regression scenario have two main limitations: (a) to minimize the number of statements presented to the developer, they omit contextual information required to truly understand the failure and, (b) to keep information propagation between the statement in the slice intact, they include lengthy computations that are not necessary to understand the failure. We evaluate and confirm these observations by surveying more than 50 practitioners from eight different countries; we further use these observations to define a new context-aware refinement-based slicing approach for debugging regression failures, which we call CoReX. We evaluate CoReX quantitatively and qualitatively, and further propose its wireframe integration into an IDE. We also conduct interviews with five senior software developers in industry, evaluating the usefulness of such an integration. We believe our work provides grounds for efficient integration of slicing-based debugging approaches into existing development practices.