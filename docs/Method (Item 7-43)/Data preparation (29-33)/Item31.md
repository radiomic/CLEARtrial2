---
title: Item#31
layout: home
parent: Data preparation (29-33)
grand_parent: Method (Item#7-43)
nav_order: 31
---

## CLEAR item#31


“Details of segmentation reliability analysis. Describe the reliability analysis done to assess the influence of segmentation differences. An intra- and inter-rater reproducibility analysis must be considered in manual and semi-automatic methods. Provide details about the statistical tests used for the reliability analysis (e.g., intraclass correlation coefficient along with types). Mention the independence of assessment. Clearly state the reliability analysis is performed using the training set only.”  [1] (from [the article by Kocak et al.](https://insightsimaging.springeropen.com/articles/10.1186/s13244-023-01415-8); licensed under CC BY 4.0)


### Reporting examples for CLEAR item#31

> **Example#1.** “According to the ICC guidelines by Koo et al., we designed our study to meet the numerical requirements of a reliability analysis in terms of both patients and observers involved, namely 30 lesions and 3 different readers. […] Texture feature interobserver reliability was assessed using a two-way, random-effects, single-rater, absolute agreement ICC. Features were considered stable when achieving good (0.75 ≤ ICC < 0.9) to excellent (ICC ≥ 0.9) interobserver reliability.” [2] (from the article by Gitto et al.; licensed under CC BY 4.0; references removed)

> **Example#2.** “To select radiomics features that discriminated the low-risk and intermediate-high-risk groups of Leibovich for localized ccRCC patients. First, the ROI of the tumor was outlined by two radiologists (reader1 and reader2) from 30 randomly selected localized ccRCC patients with three-phase CT images to evaluate inter-observer reproducibility. After 2 weeks, the tumor ROI of these 30 ccRCC patients was repeatedly outlined by reder1 to evaluate intra-observer reproducibility. Second, inter- and intra-class correlation coefficients (ICCs) were used to evaluate the inter-observer reliability and intra-observer reproducibility of feature extraction. An ICC greater than 0.75 indicates satisfactory inter- and intra-observer reproducibility.” [3] (from the article by Liu et al.; licensed under CC BY 4.0)

> **Example#3.** “A total of 107 radiomic features comprising 18 first-order statistic features, 24 gray-level co-occurrence matrix (glcm) features, 14 gray-level dependence matrix (gldm) features, 16 gray-level run-length matrix (glrlm) features, 16 gray-level size zone matrix (glszm) features, 5 neighboring gray-tone difference matrix (ngtdm) features, and 14 shape features were extracted from the manual and automated liver segmentations using the software PyRadiomics (v3.0) and their agreement was assessed using the ICC(3,1)” [4] (from the article by Gross et al.; licensed under CC BY 4.0)


### Explanation and elaboration of CLEAR item#31

In item#31, the significance of reporting the reliability analysis of segmentation is emphasized. Subtle differences in segmentation strategy might significantly affect radiomic features and consecutively decrease their predictive power [5, 6]. Therefore, authors need to provide information on the reliability of the radiomic features, excluding those radiomics features that are less reliable and therefore less reproducible. This step is fundamental to ensure reproducibility of the study design and improve clinical transferability of radiomics results.

### References

{: .fs-2 }

1. 	Kocak B, Baessler B, Bakas S, et al (2023) CheckList for EvaluAtion of Radiomics research (CLEAR): a step-by-step reporting guideline for authors and reviewers endorsed by ESR and EuSoMII. Insights Imaging 14:75. https://doi.org/10.1186/s13244-023-01415-8
2. 	Gitto S, Cuocolo R, Emili I, et al (2021) Effects of Interobserver Variability on 2D and 3D CT- and MRI-Based Texture Feature Reproducibility of Cartilaginous Bone Tumors. J Digit Imaging 34:820–832. https://doi.org/10.1007/s10278-021-00498-3
3. 	Liu H, Wei Z, Xv Y, et al (2023) Validity of a multiphase CT-based radiomics model in predicting the Leibovich risk groups for localized clear cell renal cell carcinoma: an exploratory study. Insights Imaging 14:167. https://doi.org/10.1186/s13244-023-01526-2
4. 	Gross M, Huber S, Arora S, et al (2024) Automated MRI liver segmentation for anatomical segmentation, liver volumetry, and the extraction of radiomics. Eur Radiol. https://doi.org/10.1007/s00330-023-10495-5
5. 	Poirot MG, Caan MWA, Ruhe HG, et al (2022) Robustness of radiomics to variations in segmentation methods in multimodal brain MRI. Sci Rep 12:16712. https://doi.org/10.1038/s41598-022-20703-9
6. 	Kocak B, Ates E, Durmaz ES, et al (2019) Influence of segmentation margin on machine learning-based high-dimensional quantitative CT texture analysis: a reproducibility study on renal clear cell carcinomas. Eur Radiol 29:4765–4775. https://doi.org/10.1007/s00330-019-6003-8





[Back](https://radiomic.github.io/CLEAR-E3/docs/Item2.html){: .btn .btn-purple .mr-5 }
[Next](https://radiomic.github.io/CLEAR-E3/docs/Item4.html){: .btn .btn-purple   }
