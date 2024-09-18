---
layout: default
title: CoReX Evaluation
nav_order: 4
has_children: false
permalink: /docs/RQ2_CoReX_Evalutation
---

## Program Subjects: 
We borrowed the evaluation dataset from existing work [InPreSS](https://ieeexplore.ieee.org/abstract/document/10172711), 
which includes 278 failures from six projects of the popular Defects4J benchmark and 8 large client-library project pairs with upgrade failures from LibRench.

Here is the complete list of subjects (project names and failure IDs):

* ### [RQ2_subjects](../../assets/results/RQ2-Subjects.xlsx)

The subject source codes are available for download using the following links: 

* ### [Defects4J](https://zenodo.org/record/7683853#.Y_3L1y-975g)

* ### [LibRench](https://zenodo.org/record/7683853/files/InPreSSBench.zip?download=1)

---
---
## Results
The detailed information about experiment results is provided below:

* ### [RQ2_results](../../assets/results/RQ2-Results.xlsx)

The two spreadsheets, "Reduction Rate" and "E_inspect," present detailed results for each of the 286 subjects, grouped by project.
"Reduction Rate" shows slice sizes and reduction rates achieved by synchronized, dual, InPreSS, and CoReX slices, with results reported separately for the old and new program versions.
"E_inspect" indicates whether each technique (Dual slice, InPreSS, CoReX) reaches the first changed statement by inspecting a set number of statements. For example, columns 2, 3, and 4 show the results after inspecting 5 statements from Dual, InPreSS, and CoReX, respectively.
