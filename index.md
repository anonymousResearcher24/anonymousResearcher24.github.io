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

By surveying more than 50 practitioners from eight different countries, we observe that existing slicing-based approaches for the regression scenario have two main limitations: (a) to minimize the number of statements presented to the developer, they omit contextual information required to truly understand the failure and, (b) to keep information propagation between the statement in the slice intact, they include lengthy computations that are not necessary to understand the failure. We further use these observations to define a new slicing approach for debugging regression failures, called CoReX. We quantitatively evaluate CoReX on a large number of subjects and metrics used in prior work, calculating the reduction rate it achieves and the position of the first changed statements in its slice. The results of our evaluation show that, in addition to being more aligned with developers’ needs, CoReX performs comparably with other tools on these two metrics. Finally, through a number of interviews and online questionnaires, we evaluate the practicality of and concrete ideas for integrating CoReX and similar tools into existing IDEs. We believe our work provides grounds for efficient integration of slicing-based debugging approaches into existing development practices.