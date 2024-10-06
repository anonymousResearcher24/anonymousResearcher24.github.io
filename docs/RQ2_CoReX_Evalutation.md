---
layout: default
title: CoReX Evaluation
nav_order: 4
has_children: false
permalink: /docs/RQ2_CoReX_Evalutation
---

## Program Subjects: 
We borrowed the evaluation dataset that includes 286 subjects from existing work [InPreSS](https://ieeexplore.ieee.org/abstract/document/10172711),
which includes 278 failures from six projects of the popular Defects4J benchmark (download [here](https://zenodo.org/record/7683853#.Y_3L1y-975g)) and 8 large client-library project pairs with upgrade failures from LibRench (download [here](https://zenodo.org/record/7683853/files/InPreSSBench.zip?download=1)).

---

## Results
Detailed information about the experimental results is provided in the file linked below. The file includes two tabs, "Reduction Rate" and "E_inspect", each showing results for all 286 subjects, grouped by project.

The "Reduction Rate" tab shows slice sizes and reduction rates achieved by the Dual, InPreSS, and CoReX slices, with results reported separately for the old and new program versions. For comparison, we also include the size of the entire trace and the synchronized slice on this trace.

The "E_inspect" tab shows, for each compared technique, whether it was able to reach the first changed statement within a specified number of inspected statements (k=5, 10, 30, 50, 100, 200, and 500). 

* ### [Quantitative Evaluation Results](../../assets/results/QuantitativeEvaluationResults.xlsx)


