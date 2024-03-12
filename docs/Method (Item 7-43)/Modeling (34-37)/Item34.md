---
title: Item#34
layout: home
parent: Modeling (34-37)
grand_parent: Method (Item 7-43)
nav_order: 34
---

## CLEAR item#34


“Algorithm details. Provide the name and version of software programs or packages used for modeling. Refer to the related publication of the software if available. Specify the algorithms used to create models with architectural details including inputs, outputs, and all intermediate components. The description of the architecture should be complete to allow for exact replication by other investigators (also see Item#55 and Item#56). When a previously described architecture is used, refer to the previous work and specify any modification. If the final model involved an ensemble of algorithms, specify the type of ensemble (e.g., stacking, majority voting, averaging, etc.)” [1] (from [the article by Kocak et al.](https://insightsimaging.springeropen.com/articles/10.1186/s13244-023-01415-8); licensed under CC BY 4.0)


### Reporting examples for CLEAR item#34

> **Example#1.** “Two cohorts are used to construct the prediction models by combining radiomics (intensity, shape, textures) and clinical attributes (patient age, H&N type, tumour stage) via random forests classifiers and imbalance-adjustments of training samples, and the remaining two cohorts are reserved to evaluate the prediction (binary assessment of outcome) and prognostic (time-to-event assessment) performance of the corresponding models. [...] All software code including a single organized script allowing to run the experiments used to produce all the results presented in this work is freely shared under the GNU General Public License on the GitHub website at: https://github.com/mvallieres/radiomics.” [2] (from the article by Vallières et al.; licensed under CC BY 4.0)

> **Example#2.** “In this study, we aimed to evaluate diagnostic performance of an ensemble of random forest (R) models with single-sequence inputs compared to R models with multi-sequence inputs for differentiating benign and malignant soft tissue tumors. […] We used Python to construct the classification model with the least absolute shrinkage and selection operator (Lasso) regression and R algorithm. […] The parameters for Lasso regression are summarized in the S1 Appendix. The R classifier is a well-established classifier in radiomics and is used to produce multiple decision trees. […]  R algorithm itself is also based on ensemble learning method, but it generates the machine learning model based on bootstrapping of features to make subgroups for multiple decision trees. […] In the ensemble model, the final classification was determined by soft voting using averaged probability from five, single-sequence-based R models. […] The hyperparameters were manually tuned in the type-1 radiomics models (See S2 Appendix for further details) and determined via the Grid Search algorithm in each of the five models consisting of the type-2 ensemble model (See S3 and S4 Appendices for further details). […] All statistical tests were performed using R version 4.0.0 (http://www.r-project.org/) and MedCalc for Windows, version 19.0 (MedCalc Software, Ostend, Belgium).” (Lee S et al) [3] (from the article by Lee et al.; licensed under CC BY 4.0)

### Explanation and elaboration of CLEAR item#34

Reproducibility of model results is another often unfulfilled need in this area. By providing as much detailed information as possible about the learning algorithm, interinstitutional cooperation is eased, allowing replication of the resulting models, while promoting transparency for scrutiny and development of scientific findings [4]. 

### References

{: .fs-2 }

1. 	Kocak B, Baessler B, Bakas S, et al (2023) CheckList for EvaluAtion of Radiomics research (CLEAR): a step-by-step reporting guideline for authors and reviewers endorsed by ESR and EuSoMII. Insights Imaging 14:75. https://doi.org/10.1186/s13244-023-01415-8
2. 	Vallières M, Kay-Rivest E, Perrin LJ, et al (2017) Radiomics strategies for risk assessment of tumour failure in head-and-neck cancer. Sci Rep 7:10117. https://doi.org/10.1038/s41598-017-10371-5
3. 	Lee S, Lee S-Y, Jung J-Y, et al (2023) Ensemble learning-based radiomics with multi-sequence magnetic resonance imaging for benign and malignant soft tissue tumor differentiation. PLOS ONE 18:e0286417. https://doi.org/10.1371/journal.pone.0286417
4. 	Kazmierski M, Welch M, Kim S, et al (2023) Multi-institutional Prognostic Modeling in Head and Neck Cancer: Evaluating Impact and Generalizability of Deep Learning and Radiomics. Cancer Res Commun 3:1140–1151. https://doi.org/10.1158/2767-9764.CRC-22-0152


[Back](https://radiomic.github.io/CLEAR-E3/docs/Item2.html){: .btn .btn-purple .mr-5 }
[Next](https://radiomic.github.io/CLEAR-E3/docs/Item4.html){: .btn .btn-purple   }
