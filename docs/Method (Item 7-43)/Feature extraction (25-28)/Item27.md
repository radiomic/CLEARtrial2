---
title: Item#27
layout: home
parent: Feature extraction (25-28)
grand_parent: Method (Item#7-43)
nav_order: 27
---

## CLEAR item#27


“Number of features. Indicate the total number of features per instance. If applicable, provide the number of features per imaging modality and its components (e.g., phase for CT, sequence for MRI, etc.).”  [1] (from [the article by Kocak et al.](https://insightsimaging.springeropen.com/articles/10.1186/s13244-023-01415-8); licensed under CC BY 4.0)


### Reporting examples for CLEAR item#27

> **Example#1.** “In total, we extracted 107 radiomics features (Supplementary Materials) from PCAT surrounding plaques with the reference of the image biomarker standardization initiative (IBSI).” [2] (from [the article by Shang et al.](https://doi.org/10.1007/s00330-021-08109-z); licensed under CC BY 4.0)

> **Example#2.** “In total, 43 features were extracted from five-time points, resulting in 215 features for each case, which described the dynamic evolution of the contrast agent in the focus. […] three of the extracted features refer to the pre-contrast image and 32 refer to images acquired after the contrast injection split over the different time points” [3] (from [the article by D’Amico et al.](https://doi.org/10.1186/s41747-019-0131-4); licensed under CC BY 4.0)

### Explanation and elaboration of CLEAR item#27

There is a vast array of radiomics features that can be extracted from a target volume in the image. Additionally, several imaging volumes of the same subject may be involved in the study. To ensure transparency regarding feature generation and to provide insights about the actual dimensionality of the study that is important to assess for potential overfitting, it is crucial to include in the methods section the number of features calculated, along with details for each separate imaging volume. It is also pertinent to specify how many features, and from which imaging volumes, constitute the inputs for the final models. This information allows for the assessment of practical complexity and facilitates the comparison of different radiomics models for a similar clinical task. Furthermore, it is also relevant to evaluate whether the sample size was adequate for model development [4].

### References

{: .fs-2 }

1. 	Kocak B, Baessler B, Bakas S, et al (2023) CheckList for EvaluAtion of Radiomics research (CLEAR): a step-by-step reporting guideline for authors and reviewers endorsed by ESR and EuSoMII. Insights Imaging 14:75. https://doi.org/10.1186/s13244-023-01415-8
2. 	Shang J, Ma S, Guo Y, et al (2022) Prediction of acute coronary syndrome within 3 years using radiomics signature of pericoronary adipose tissue based on coronary computed tomography angiography. Eur Radiol 32:1256–1266. https://doi.org/10.1007/s00330-021-08109-z
3. 	D’Amico NC, Grossi E, Valbusa G, et al (2020) A machine learning approach for differentiating malignant from benign enhancing foci on breast MRI. Eur Radiol Exp 4:5. https://doi.org/10.1186/s41747-019-0131-4
4. 	Riley RD, Ensor J, Snell KIE, et al (2020) Calculating the sample size required for developing a clinical prediction model. BMJ 368:m441. https://doi.org/10.1136/bmj.m441

[Back](https://radiomic.github.io/CLEAR-E3/docs/Method%20(Item%207-43)/Feature%20extraction%20(25-28)/Item26.html){: .btn .btn-purple .mr-5 }
[Next](https://radiomic.github.io/CLEAR-E3/docs/Method%20(Item%207-43)/Feature%20extraction%20(25-28)/Item28.html){: .btn .btn-purple   }
