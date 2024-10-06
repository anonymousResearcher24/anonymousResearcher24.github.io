---
layout: default
title: CoReX Evaluation
nav_order: 4
has_children: false
permalink: /docs/RQ2_CoReX_Evalutation
---

## Program Subjects: 
We borrowed the evaluation dataset that includes 286 subjects from existing work [InPreSS](https://ieeexplore.ieee.org/abstract/document/10172711), 
which includes 278 failures from six projects of the popular [Defects4J](https://zenodo.org/record/7683853#.Y_3L1y-975g) benchmark and 8 large client-library project pairs with upgrade failures from [LibRench](https://zenodo.org/record/7683853/files/InPreSSBench.zip?download=1).

We borrowed the evaluation dataset that includes 286 subjects from existing work [InPreSS](https://ieeexplore.ieee.org/abstract/document/10172711),
which includes 278 failures from six projects of the popular Defects4J (download [here](https://zenodo.org/record/7683853#.Y_3L1y-975g)) benchmark and 8 large client-library project pairs with upgrade failures from LibRench (download [here](https://zenodo.org/record/7683853/files/InPreSSBench.zip?download=1)).

---
---
## Results
Detailed information about the experimental results is provided in the file linked below. The file includes two tabs,  "Reduction Rate" and "E_inspect", each showing results for all 286 subjects, grouped by project.
The "Reduction Rate" tab shows slice sizes and reduction rates achieved by the synchronized, Dual, InPreSS, and CoReX slices, with results reported separately for the old and new program versions.
The "E_inspect" tab, however, focuses on the techniques compared for reaching the first changed statement within a specified number of inspected statements. It provides "TRUE" or "FALSE" values for each technique (Dual, InPreSS, and CoReX) to indicate if they reach the first changed statement within the given statement count, while synchronized slices in the “Reduction Rate” tab serves as a baseline rather than a directly comparable technique in this context. 

* ### [RQ2_results](../../assets/results/RQ2-Results.xlsx)


