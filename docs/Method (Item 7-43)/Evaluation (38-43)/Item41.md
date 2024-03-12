---
title: Item#41
layout: home
parent: Evaluation (38-43)
grand_parent: Method (Item#7-43)
nav_order: 41
---

## CLEAR item#41


“Statistical performance comparison (e.g., DeLong’s test). Specify the statistical software and version used. Indicate which method was used for the comparison of the model performance such as the DeLong’s test, McNemar’s test, or Bayesian approaches. Provide a statistical threshold for the comparison (e.g., p < 0.05) along with confidence intervals if applicable to the method or metric. Also, state if multiplicity is considered and corrected when comparing multiple models (e.g., p-value adjustment, Bonferroni correction, false-discovery rate). Report threshold values to stratify data into groups for statistical testing (e.g., the operating point on the receiver operating characteristic [ROC] curve to define the confusion matrix, and cut-off values for defining strata in survival analysis).” [1] (from [the article by Kocak et al.](https://insightsimaging.springeropen.com/articles/10.1186/s13244-023-01415-8); licensed under CC BY 4.0)


### Reporting examples for CLEAR item#41

> **Example#1.** “Model accuracy (n correct predictions/total cases) in each test set was also compared with a baseline reference (no information rate, i.e., the class mode) using a binomial test and an expert radiologist’s predictions using McNemar’s tests. A p < 0.05 was considered statistically significant, with correction for multiple comparisons when required. The statistical analysis was performed using the R software environment.” [2] (from the article by Cuocolo et al.; licensed under CC BY 4.0)

> **Example#2.** “A DeLong test was used to determine if there was a statistically significant difference in the performance between the three models (CC vs CC + MLO, MLO vs CC + MLO, and CC vs MLO model). A two-sided p value of < 0.05 was used as the criterion of statistically significant difference. […] All radiomics analysis pipeline and statistical analysis were conducted using MATLAB R2021a (MathWorks, Natick, MA, USA) apart from the DeLong test which was performed using pROC package in RStudio 2021.09.0.351 (RStudio Team, Boston, MA, USA)/R 4.1.2 (R Core Team, Vienna, Austria).” [3] (from the article by  Siviengphanom et al.; licensed under CC BY 4.0)

### Explanation and elaboration of CLEAR item#41

A wide variety of classifiers and feature selection algorithms is available for radiomics modeling, and it is often difficult to establish in advance what combination would optimize the final model performance [4]. Thus, a common approach is to train multiple models testing different combinations of algorithms/classifiers and select the best performing one using appropriate statistical comparison. Such performance comparisons are also needed to explore the potential advantage of radiomics models over non-radiomics ones, as discussed in item #42. A detailed description of the applied statistical methodology as well as of the criteria for interpreting the results is necessary not only to ensure the transparency of the study and the robustness of the results but is at the same time a prerequisite for replicating the findings on independent datasets.

### References

{: .fs-2 }

1. 	Kocak B, Baessler B, Bakas S, et al (2023) CheckList for EvaluAtion of Radiomics research (CLEAR): a step-by-step reporting guideline for authors and reviewers endorsed by ESR and EuSoMII. Insights Imaging 14:75. https://doi.org/10.1186/s13244-023-01415-8
2. 	Cuocolo R, Stanzione A, Faletti R, et al (2021) MRI index lesion radiomics and machine learning for detection of extraprostatic extension of disease: a multicenter study. Eur Radiol 31:7575–7583. https://doi.org/10.1007/s00330-021-07856-3
3. 	Siviengphanom S, Gandomkar Z, Lewis SJ, Brennan PC (2023) Global Radiomic Features from Mammography for Predicting Difficult-To-Interpret Normal Cases. J Digit Imaging 36:1541–1552. https://doi.org/10.1007/s10278-023-00836-7
4. 	Decoux A, Duron L, Habert P, et al (2023) Comparative performances of machine learning algorithms in radiomics and impacting factors. Sci Rep 13:14069. https://doi.org/10.1038/s41598-023-39738-7



[Back](https://radiomic.github.io/CLEAR-E3/docs/Item2.html){: .btn .btn-purple .mr-5 }
[Next](https://radiomic.github.io/CLEAR-E3/docs/Item4.html){: .btn .btn-purple   }
