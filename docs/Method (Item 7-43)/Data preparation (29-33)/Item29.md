---
title: Item#29
layout: home
parent: Data preparation (29-33)
grand_parent: Method (Item#7-43)
nav_order: 29
---

## CLEAR item#29


“Handling of missing data. State if, and how much, missing data are present in the study. If so, provide details as to how it was addressed (e.g., deletion, substitution, or imputation).”  [1] (from [the article by Kocak et al.](https://insightsimaging.springeropen.com/articles/10.1186/s13244-023-01415-8); licensed under CC BY 4.0)


### Reporting examples for CLEAR item#29

> **Example#1.** “This study deleted categories with missing values greater than 25%, and MICEforest multiple interpolation methods were used to fill the missing values. […] The items and proportions of missing data that were ultimately included in the study and subjected to multiple imputations using the MICEforest method are shown in Figure 5.” [2] (from [the article by Lin et al.](https://doi.org/10.3389/fonc.2022.937277); licensed under CC BY 4.0)

> **Example#2.** “[…] missing values were imputed with a 𝑘-nearest neighbors imputer with 𝑘 = 8 and distance-based weights (see Appendix B.1 for a deeper analysis on the imputation and its parameters).” [3] (from [the article by Isaksson et al.](https://doi.org/10.1016/j.imu.2023.101161); licensed under CC BY 4.0)

### Explanation and elaboration of CLEAR item#29

Addressing missing values involves acknowledging the potential occurrence of data gaps, encompassing both clinical and radiomic features. In clinical scenarios, complete deletion of instances with missing values may be impractical due to the necessity of utilizing predictive models despite incomplete data. An alternative approach involves the imputation of missing values. This process uses statistical techniques, ranging from simple methods such as substituting missing values with the mean, mode, or median, to more intricate strategies involving multivariate modeling [4]. By explicitly disclosing the presence and extent of missing data in the study, along with detailing the chosen imputation methodology, researchers enhance the transparency of their radiomics study. This also allows for a more comprehensive understanding of the dataset's integrity and potential impact on study outcomes as well as possible use cases of the developed model.

### References

{: .fs-2 }

1. 	Kocak B, Baessler B, Bakas S, et al (2023) CheckList for EvaluAtion of Radiomics research (CLEAR): a step-by-step reporting guideline for authors and reviewers endorsed by ESR and EuSoMII. Insights Imaging 14:75. https://doi.org/10.1186/s13244-023-01415-8
2. 	Lin Q, Wu HJ, Song QS, Tang YK (2022) CT-based radiomics in predicting pathological response in non-small cell lung cancer patients receiving neoadjuvant immunotherapy. Front Oncol 12. https://doi.org/10.3389/fonc.2022.937277
3. 	Isaksson LJ, Repetto M, Summers PE, et al (2023) High-performance prediction models for prostate cancer radiomics. Inform Med Unlocked 37:101161. https://doi.org/10.1016/j.imu.2023.101161
4. 	Stanzione A, Cuocolo R, Ugga L, et al (2022) Oncologic Imaging and Radiomics: A Walkthrough Review of Methodological Challenges. Cancers 14:4871. https://doi.org/10.3390/cancers14194871


[Back](https://radiomic.github.io/CLEAR-E3/docs/Method%20(Item%207-43)/Feature%20extraction%20(25-28)/Item28.html){: .btn .btn-purple .mr-5 }
[Next](https://radiomic.github.io/CLEAR-E3/docs/Method%20(Item%207-43)/Data%20preparation%20(29-33)/Item30.html){: .btn .btn-purple   }
