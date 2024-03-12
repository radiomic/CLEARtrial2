---
title: Item#38
layout: home
parent: Evaluation (38-43)
grand_parent: Method (Item#7-43)
nav_order: 38
---

## CLEAR item#38


“Testing technique (e.g., internal, external). Clearly state whether the model was internally or externally tested. The term “external testing” should only be used for the process that involves data usage from different institutions. In the case of external testing, specify the number of sites providing data and further details about whether they are used for multiple testing or in a single test. Describe the data characteristics and state if there are any differences among training, validation, internal testing, and external testing datasets (e.g., different scanners, different readers for segmentation, different ethnicity). Again, note that any test data should only be used once for evaluation to prevent biased performance metric estimates.” [1] (from [the article by Kocak et al.](https://insightsimaging.springeropen.com/articles/10.1186/s13244-023-01415-8); licensed under CC BY 4.0)


### Reporting examples for CLEAR item#38

> **Example#1.** “The models with the highest c-index for each method created at a single institution were re-tested on external data at the other institution. Kaplan–Meier survival plots were produced from the external test-set.” [2] (from [the article by Frood et al.](https://doi.org/10.1007/s00330-023-10340-9); licensed under CC BY 4.0) 

> **Example#2.** “In this study, 425 patients with primary localized ccRCC from two medical centers were retrospectively enrolled. […] The enrolled 381 patients from center 1 were randomized 7:3 into the training cohort and validation cohort, whereas 44 patients from center 2 were used as an independent external testing cohort.” [3] (from [the article by Liu et al.](https://doi.org/10.1186/s13244-023-01526-2); licensed under CC BY 4.0)

> **Example#3.** “This is a multicenter retrospective study that includes four institutes: University Hospital “Città della Salute e della Scienza” of Turin (center A), “Mauriziano Umberto I” Hospital of Turin (center B), Candiolo Cancer Institute (center C), and Federico II Hospital of Naples (center D). […] MRI examinations were performed using 1.5T scanners at centers A, B, and C (Achieva Philips Medical Systems, Ingenia Philips Medical Systems, and Optimae GE Healthcare, respectively) and a 3T scanner at center D (Magnetom Trio Siemens Medical Solutions). […] During the development of the radiomics signature, 26 combinations of feature selection (FS) methods and classifiers/regressors were fine-tuned using only patients from centers A and B (construction dataset). […] The validation step was performed by applying the previously selected model on the validation set, which included only patients that were left out from the model development phase, i.e., from centers C and D […]” [4] (from [the article by Nicoletti et al.](https://doi.org/10.3390/cancers16010203); licensed under CC BY 4.0)

### Explanation and elaboration of CLEAR item#38

The clear explanation of the testing technique allows the evaluation of the generalizability and validity of the radiomic model and the relative process of validation. A clinical model can be useful and applicable in two scenarios: first, in the accurate classification of patients into different clinical or prognostic groups, or to estimate the probability of determining clinical or prognostic parameters in individual patients: in other words, the clinical model is predictive of an endpoint. A fundamental aspect of prediction is the capability of the model to achieve an acceptable performance on a population which is different from the one used to build the model itself. This concept is usually indicated as generalizability or validity, and the process is called validation (or “testing” according to CLEAR’s terminology) [5]. In general, the radiomic model is built on the training cohort, where the correlation between the extracted features and the outcome is explored. The validation cohort is used to select and optimize the parameters of the trained model, while the testing dataset contains cases completely unseen by the trained model. Therefore, it is recommended to use datasets from different centers (i.e., external testing), to split the dataset from a single center in different cohorts (i.e., internal testing) following specific rules, or to develop retrospectively the model that is prospectively tested. The declaration and the analysis of differences among the training/validation (i.e., development) and testing datasets, as well as the methodology of image processing, data extraction, and analysis are strongly recommended [6].

### References

{: .fs-2 }

1. 	Kocak B, Baessler B, Bakas S, et al (2023) CheckList for EvaluAtion of Radiomics research (CLEAR): a step-by-step reporting guideline for authors and reviewers endorsed by ESR and EuSoMII. Insights Imaging 14:75. https://doi.org/10.1186/s13244-023-01415-8
2. 	Frood R, Mercer J, Brown P, et al (2023) Training and external validation of pre-treatment FDG PET-CT-based models for outcome prediction in anal squamous cell carcinoma. Eur Radiol. https://doi.org/10.1007/s00330-023-10340-9
3. 	Liu H, Wei Z, Xv Y, et al (2023) Validity of a multiphase CT-based radiomics model in predicting the Leibovich risk groups for localized clear cell renal cell carcinoma: an exploratory study. Insights Imaging 14:167. https://doi.org/10.1186/s13244-023-01526-2
4. 	Nicoletti G, Mazzetti S, Maimone G, et al (2024) Development and Validation of an Explainable Radiomics Model to Predict High-Aggressive Prostate Cancer: A Multicenter Radiomics Study Based on Biparametric MRI. Cancers 16:203. https://doi.org/10.3390/cancers16010203
5. 	Altman DG, Royston P (2000) What do we mean by validating a prognostic model? Stat Med 19:453–473. https://doi.org/10.1002/(sici)1097-0258(20000229)19:4<453::aid-sim350>3.0.co;2-5
6. 	Moons KGM, Altman DG, Reitsma JB, et al (2015) Transparent Reporting of a multivariable prediction model for Individual Prognosis or Diagnosis (TRIPOD): explanation and elaboration. Ann Intern Med 162:W1-73. https://doi.org/10.7326/M14-0698


[Back](https://radiomic.github.io/CLEAR-E3/docs/Method%20(Item%207-43)/Modeling%20(34-37)/Item37.html){: .btn .btn-purple .mr-5 }
[Next](https://radiomic.github.io/CLEAR-E3/docs/Method%20(Item%207-43)/Evaluation%20(38-43)/Item39.html){: .btn .btn-purple   }
