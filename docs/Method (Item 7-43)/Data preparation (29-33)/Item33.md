---
title: Item#33
layout: home
parent: Data preparation (29-33)
grand_parent: Method (Item#7-43)
nav_order: 33
---

## CLEAR item#33


“Dimension reduction details. Specify the dimension reduction methods used, if applicable (e.g., collinearity analysis, reproducibility analysis, algorithm-based feature selection). Provide details about the statistical methods used. For example, provide the relevant statistical cut-off values for each step (e.g., features with intraclass correlation coefficient ≤ 0.9 are excluded). Clearly state the dimension reduction that is performed using the training set. Specify how the final number of features is achieved, for instance, the “rule of thumb” of ten features maximum for each instance.” [1] (from [the article by Kocak et al.](https://insightsimaging.springeropen.com/articles/10.1186/s13244-023-01415-8); licensed under CC BY 4.0)


### Reporting examples for CLEAR item#33

> **Example#1.** “According to the radiomics features extracted from the twice tumor segmentation, the intra-class correlation coefficient (ICC) was calculated, and radiomics features with an ICC greater than 0.80 were selected. […] To select radiomics features, a least absolute shrinkage and selection operator (LASSO) algorithm was employed in conjunction with fivefold cross-validation, which was used to identify the best lambda value with the lowest prediction error.”  [1] (from the article by Wang et al.; licensed under CC BY 4.0)

> **Example#2.** “Minimum redundancy maximum relevance (mRMR) was used to eliminate redundant and irrelevant features, retain the optimal ones, filter out the optimal feature subset through the least absolute shrinkage and selection operator (LASSO) algorithm, and build a final model.” [2] (from the article by Ge et al.; licensed under CC BY 4.0)

### Explanation and elaboration of CLEAR item#33

Radiomics analysis yields many extracted features from each segmentation. A large number of these features are not associated with the outcome or they are correlated to each other, namely they are redundant.  The main risk of selecting redundant features is  model overfitting. Dimension reduction of the radiomic features is crucial to build an adequate radiomics model. This is a multi-step process, leading to exclusion of non-reproducible, redundant, and non-relevant features from the final model [3]. Several reduction methods have been described, including supervised and unsupervised methods [4]. Features with low reproducibility assessed with the intra- and inter-observer reliability analysis should be excluded from the model. While there is no consensus on the optimal final number of features to be included in the model, the need of ten samples for each feature included in the model has been advocated in binary classification models (also known as “rule of thumb”), particularly for logistic regression-based analyses [5].

### References

{: .fs-2 }

1. 	Wang H, Xie M, Chen X, et al (2023) Radiomics analysis of contrast-enhanced computed tomography in predicting the International Neuroblastoma Pathology Classification in neuroblastoma. Insights Imaging 14:106. https://doi.org/10.1186/s13244-023-01418-5
2. 	Ge X-Y, Lan Z-K, Lan Q-Q, et al (2023) Diagnostic accuracy of ultrasound-based multimodal radiomics modeling for fibrosis detection in chronic kidney disease. Eur Radiol 33:2386–2398. https://doi.org/10.1007/s00330-022-09268-3
3. 	van Timmeren JE, Cester D, Tanadini-Lang S, et al (2020) Radiomics in medical imaging—“how-to” guide and critical reflection. Insights Imaging 11:91. https://doi.org/10.1186/s13244-020-00887-2
4. 	Wagner MW, Namdar K, Biswas A, et al (2021) Radiomics, machine learning, and artificial intelligence-what the neuroradiologist needs to know. Neuroradiology 63:1957–1967. https://doi.org/10.1007/s00234-021-02813-9
5. 	Gillies RJ, Kinahan PE, Hricak H (2016) Radiomics: Images Are More than Pictures, They Are Data. Radiology 278:563–577. https://doi.org/10.1148/radiol.2015151169

[Back](https://radiomic.github.io/CLEAR-E3/docs/Method%20(Item%207-43)/Data%20preparation%20(29-33)/Item32.html){: .btn .btn-purple .mr-5 }
[Next](https://radiomic.github.io/CLEAR-E3/docs/Method%20(Item%207-43)/Modeling%20(34-37)/Item34.html){: .btn .btn-purple   }
