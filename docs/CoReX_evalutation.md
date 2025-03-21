---
layout: default
title: CoReX Evaluation
nav_order: 4
has_children: false
permalink: /docs/CoReX_evalutation
---

## RQ1 and RQ2: Program Subjects
We borrowed the evaluation dataset that includes 286 subjects from existing work [InPreSS](https://ieeexplore.ieee.org/abstract/document/10172711),
which includes 278 failures from six projects of the popular Defects4J benchmark (download [here](https://zenodo.org/record/7683853#.Y_3L1y-975g)) and 8 large client-library project pairs with upgrade failures from LibRench (download [here](https://zenodo.org/record/7683853/files/InPreSSBench.zip?download=1)).

---

## RQ1 and RQ2: Results
Detailed information about the experimental results is provided in the file linked below. The file includes two tabs, "Reduction Rate" and "E_inspect", each showing results for all 286 subjects, grouped by project.

The "RQ1-Reduction Rate" tab shows slice sizes and reduction rates achieved by the Dual, InPreSS, CoReXI, and CoReX slices, with results reported separately for the old and new program versions. For comparison, we also include the size of the entire trace and the synchronized slice on this trace.

The "RQ2-Time" tab shows the runtime measurements (in minutes) for Dual, InPreSS, CoReXI, and CoReX. We separate the tools’ runtime into that for the slicing and slice summarization. 

* ### [Quantitative Evaluation Results](../../assets/results/QuantitativeEvaluationResults.xlsx)

---

## RQ3: Program Subjects
We re-considered code samples used in the [study] (https://anonymousresearcher24.github.io/docs/user_study)

---

## RQ2: Results

While the raw data obtained in this study cannot be shared because of privacy issues, we provided the Precision, Recall, and F-Measure calculated for each developer’s selection individually in the file linked below. 

* ### [Alignment Results](../../assets/results/AlignmentResults.xlsx)