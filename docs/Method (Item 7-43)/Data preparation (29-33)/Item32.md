---
title: Item#32
layout: home
parent: Data preparation (29-33)
grand_parent: Method (Item 7-43)
nav_order: 32
---

## CLEAR item#32


“Feature scaling details (e.g., normalization, standardization). If applicable, describe the normalization technique applied to the radiomic feature data (e.g., minimum–maximum normalization, standardization, logarithmic transformation, ComBat normalization [choice of the batch, parametric or not, with or without empirical Bayes]). Specify the normalization scale. It is important to emphasize that this procedure is applied to the numeric radiomic feature data, not the images, in the training set and independently applied to the validation and test sets.” [1] (from [the article by Kocak et al.](https://insightsimaging.springeropen.com/articles/10.1186/s13244-023-01415-8); licensed under CC BY 4.0)


### Reporting examples for CLEAR item#32

> **Example#1.** “Feature values were normalized to the (0,1) interval.” [2] (from the article by Kaissis et al.; licensed under CC BY 4.0)

> **Example#2.** “Since images were acquired on multisite with different MRI acquisition protocols, a stage of harmonisation is necessary to remove the batch effect introduced by technical heterogeneity on radiomic data. Therefore, we apply the ComBat algorithm, a popular batch effect correction tool” [3] (from the article by Fradet et al.; licensed under CC BY 4.0)

> **Example#3.** “To mitigate the risk of “snooping”—the inadvertent leakage of information from the test set that might lead to a form of overfitting—we partitioned our data into training and test sets (with a ratio of 80/20) prior to standardization.” [4] (from the article by Triantafyllou et al.; licensed under CC BY 4.0)


### Explanation and elaboration of CLEAR item#32

Item#32 of the CLEAR checklist focuses on the detailing of feature scaling techniques applied to radiomic data, to enhance the comparability and reliability of the extracted features. Example#1 shows min-max normalization which is one of the many normalization techniques that can be used in radiomic feature value standardization. [5] This is critical for ensuring that the features are on a comparable scale, especially important in machine learning models where feature scale can significantly impact performance. Both Example#1 and Example#2 emphasize the application of these methods to the radiomic data, not the images themselves. Applying such corrections to the data, particularly as in Example#2, may allow maintaining the integrity of the analysis by removing technical heterogeneity that could otherwise skew results. Example#3 highlights the practice of partitioning data into training and test sets before feature scaling to avoid "snooping", the inadvertent leakage of information from the test set, which could lead to overfitting. 

### References

{: .fs-2 }

1. 	Kocak B, Baessler B, Bakas S, et al (2023) CheckList for EvaluAtion of Radiomics research (CLEAR): a step-by-step reporting guideline for authors and reviewers endorsed by ESR and EuSoMII. Insights Imaging 14:75. https://doi.org/10.1186/s13244-023-01415-8
2. 	Kaissis G, Ziegelmayer S, Lohöfer F, et al (2019) A machine learning model for the prediction of survival and tumor subtype in pancreatic ductal adenocarcinoma from preoperative diffusion-weighted imaging. Eur Radiol Exp 3:41. https://doi.org/10.1186/s41747-019-0119-0
3. 	Fradet G, Ayde R, Bottois H, et al (2022) Prediction of lipomatous soft tissue malignancy on MRI: comparison between machine learning applied to radiomics and deep learning. Eur Radiol Exp 6:41. https://doi.org/10.1186/s41747-022-00295-9
4. 	Triantafyllou M, Klontzas ME, Koltsakis E, et al (2023) Radiomics for the Detection of Active Sacroiliitis Using MR Imaging. Diagnostics 13:2587. https://doi.org/10.3390/diagnostics13152587
5. 	Demircioğlu A (2024) The effect of feature normalization methods in radiomics. Insights Imaging 15:2. https://doi.org/10.1186/s13244-023-01575-7


[Back](https://radiomic.github.io/CLEAR-E3/docs/Item2.html){: .btn .btn-purple .mr-5 }
[Next](https://radiomic.github.io/CLEAR-E3/docs/Item4.html){: .btn .btn-purple   }
