---
title: Item#26
layout: home
parent: Feature extraction (25-28)
grand_parent: Method (Item#7-43)
nav_order: 26
---

## CLEAR item#26


“Feature classes. Provide the radiomic feature classes (e.g., shape, first-order, grey-level co-occurrence matrix). Use IBSI terminology for feature classes. Specify the number of features per feature class. Mention if any feature class is excluded with reason.” [1] (from [the article by Kocak et al.](https://insightsimaging.springeropen.com/articles/10.1186/s13244-023-01415-8); licensed under CC BY 4.0)


### Reporting examples for CLEAR item#26

> **Example#1.** “[…]16 shape-related (3D), 19 intensity-related (First Order Statistics) and 75 texture-related features (Gray Level Co-occurrence Matrix, Gray Level Run Length Matrix, Gray Level Size Zone Matrix, Neighboring Gray Tone Difference Matrix and Gray Level Dependence Matrix) were extracted from each GTVt tumor region in CT using Pyradiomics v3.0.1 package (https://pyradiomics.readthedocs.io/en/latest/).” [2] (from [the article by Ma et al.](https://doi.org/10.1016/j.phro.2023.100502); licensed under CC BY 4.0)

> **Example#2.** “Radiomics analysis was performed using PyRadiomics (version 2.7.7, Harvard Medical School, Boston, MA, USA) [10.1158/0008-5472.can-17-0339], which is compliant with the Image Biomarker Standardisation Initiative (IBSI) [10.1148/radiol.2020191145]. 842 features were extracted including: shape (n = 14), first order statistics (n = 18), gray level cooccurrence matrix (GLCM) (n = 23), gray level run length matrix (GLRLM) (n = 16), gray level size zone matrix (GLSZM) (n = 16), gray level dependence matrix (GLDM) (n = 14) and neighbouring gray tone difference matrix (NGTDM) (n = 5). Wavelet filtering was also applied to these features. Shape features were only used for correlation analysis to segmentation volume. […] Shape features was excluded from the repeatability and reproducibility analysis to remove user bias from manual contouring methods.” [3] (from [the article by Brown et al.](https://doi.org/10.1016/j.phro.2023.100446); licensed under CC BY 4.0)

### Explanation and elaboration of CLEAR item#26

Item#26 is another important item in terms of reporting feature extraction settings. Providing standardized terms is also recommended to allow the reproducibility and comprehensiveness of the studies. The Image Biomarker Standardization Initiative (IBSI) produced a standardized terminology and validated a set of consensus-based reference values for radiomics features [4]. 

### References

{: .fs-2 }

1. 	Kocak B, Baessler B, Bakas S, et al (2023) CheckList for EvaluAtion of Radiomics research (CLEAR): a step-by-step reporting guideline for authors and reviewers endorsed by ESR and EuSoMII. Insights Imaging 14:75. https://doi.org/10.1186/s13244-023-01415-8
2. 	Ma B, Guo J, Chu H, et al (2023) Comparison of computed tomography image features extracted by radiomics, self-supervised learning and end-to-end deep learning for outcome prediction of oropharyngeal cancer. Phys Imaging Radiat Oncol 28:100502. https://doi.org/10.1016/j.phro.2023.100502
3. 	Brown KH, Payan N, Osman S, et al (2023) Development and optimisation of a preclinical cone beam computed tomography-based radiomics workflow for radiation oncology research. Phys Imaging Radiat Oncol 26:. https://doi.org/10.1016/j.phro.2023.100446
4. 	Zwanenburg A, Vallières M, Abdalah MA, et al (2020) The Image Biomarker Standardization Initiative: Standardized Quantitative Radiomics for High-Throughput Image-based Phenotyping. Radiology 295:328–338. https://doi.org/10.1148/radiol.2020191145

[Back](https://radiomic.github.io/CLEAR-E3/docs/Method%20(Item%207-43)/Feature%20extraction%20(25-28)/Item25.html){: .btn .btn-purple .mr-5 }
[Next](https://radiomic.github.io/CLEAR-E3/docs/Method%20(Item%207-43)/Feature%20extraction%20(25-28)/Item27.html){: .btn .btn-purple   }
