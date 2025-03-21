---
layout: default
title: Home
nav_order: 1
description: "CoReX: Context-Aware Refinement-Based Slicing for Debugging Regression Failures"
permalink: /
---

### CoReX: Context-Aware Refinement-Based Slicing for Debugging Regression Failures

---

Troubleshooting regression failures is one of the most frequent yet time-consuming development tasks. To help with this task, numerous approaches aim to narrow down developers’ attention to the subset of code statements relevant to the failure. The most prominent of these approaches are based on program slicing, as slicing not only identifies a subset of relevant statements but also maintains the flow of information between these statements.

By surveying more than 50 practitioners from eight different countries, we observe that existing dual-version slicing-based approaches have two main limitations: (a) to minimize the number of statements presented to the developer, they omit contextual information required to truly understand the failure and (b) to keep information propagation between the statements in the slice intact, they include lengthy computations that are not necessary to understand the failure. We use these observations to define a new dual-version slicing approach for regression scenarios, called CoReX. We quantitatively evaluate CoReX on a large number of subjects and metrics used in prior work, calculating the reduction rate it achieves and its alignment with developers’ expectations. The results of our evaluation show that CoReX outperforms other existing dual-version slicing techniques on both metrics. We believe our work provides grounds for efficient integration of slicing-based approaches into development workflows.