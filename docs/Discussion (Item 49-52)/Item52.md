---
title: Item#52
layout: home
parent: Discussion (Item 49-52)
nav_order: 52
---

## CLEAR item#52


“Strengths and limitations (e.g., bias and generalizability issues). Clearly state the strengths and the limitations of the current work. Any issue that may lead to potential bias, uncertainty, reproducibility, robustness, and generalizability problems should be declared.”  [1] (from [the article by Kocak et al.](https://insightsimaging.springeropen.com/articles/10.1186/s13244-023-01415-8); licensed under CC BY 4.0)


### Reporting examples for CLEAR item#52

> **Example#1.** “Our study possesses several advantages compared to previous studies on radiomics models for differentiating NP and IP. Firstly, we approached the analysis of IP and NP from a clinical perspective rather than relying solely on a database, and our study included a larger population compared to most relevant studies. Secondly, we employed three different methods of feature extraction (correlation coefficient, Boruta, and random forest), which contributed to improved diagnostic performance compared to previous radiomics models. Thirdly, we utilized multiple classifier models for classification, and some of these models demonstrated outstanding performance. Additionally, our study employed ten-fold cross-validation to validate the accuracy of the algorithm, a step that was lacking in previous studies.” [2] (from the article by Guo et al.; licensed under CC BY 4.0)

> **Example#2.** “There are some limitations to our study. First, we used the clinical standard FDG-PET/CT as a reference for classifying LNs as malignant and benign. According to the Cochrane meta-analysis, FDG-PET/CT is a very good screening tool with a summary sensitivity and specificity of 81.3% (95% CI 70.2−88.9%) and 79.4% (95% CI 70%−86.5%), respectively. However, it is still under the threshold of 95% comparing to the histopathological analysis. Second, average PET uptake time was above the recommended standard of 60 min. This might have resulted in increased LN SUVmax compared to an earlier imaging time point due to the irreversible nature of cellular FDG uptake. Comparability with other centers would therefore benefit from uniform uptake times. To encounter these methodological limitations, we included a huge number of analysed LNs (n = 1,799). Third, we have included only patients with histologically proven primary lung cancer, specifically adenocarcinoma or squamous-cell carcinoma, therefore, the results cannot be generalised on all primary lung cancer types. However, firstly the vast majority had NSCLC, specifically, adenocarcinoma and secondly, this is a preliminary study. Therefore, our promising results should encourage for further radiomics and machine learning analysis in future studies including other primary lung cancer types such as small cell lung cancer. Fourth, our analysis was based on a retrospective cohort. Therefore, selection bias and confounders cannot be fully excluded. To overcome them, we performed balancing and a multi-modeling methodology implementation with 30 times of bootstraps iterations and aggregation with 24 different combinations of classifiers and FSM. To encounter for further miscalibration and to assess the clinical benefit, we performed a decision curve analysis that incorporates both discrimination and calibration and is less sensitive to miscalibration. Depending on the model scenery, miscalibration reduces the net benefit (clinical utility); therefore, in a larger and better calibrated cohort, the clinical benefit of LASSO as a radiomics signature might be even higher than in the present study.” [3] (from the article by Gorodetski et al.; licensed under CC BY 4.0)

> **Example#2.** “This study has several limitations. Data were collected from a single centre, and additional external validation of the proposed model is required. This was, however, mitigated by the rigorous patient selection and matching, calibration, and pre-processing stages aimed at reducing overfitting and maximising the reliability of subsequent predictive modelling and cross-validation steps. Only patients with MR-visible lesions were included in the analysis, limiting generalisability of the findings, given that only 50% of patients included on AS programmes will have an MRI lesion detected. The choice of such a cohort was, however, deliberate given that the presence of MR-visible lesions is in itself a poor prognosticator of PCa progression on AS, thereby warranting further risk-stratification of lesions based on their progressive potential. Dynamic contrast-enhanced images, obtained as part of mpMRI protocol, were not used in this study due to the increasing body of evidence suggesting the non-inferiority of biparametric MRI for lesion characterisation. Furthermore, in this study we used Likert scores, which is the default system used in our department being informed by the criteria defined in PI-RADS v2.1. The systems are broadly similar, but Likert will often differ in scores 4 and 5 as it lacks a size threshold for this differentiation. The non-inferiority of Likert score assessment for the detection of clinically significant disease was documented previously.”  [4] (from the article by Sushentsev et al.; licensed under CC BY 4.0)

### Explanation and elaboration of CLEAR item#52

The strengths of the study should be explicitly highlighted, emphasizing aspects such as well-defined methodologies, rigorous data collection, or innovative approaches employed. This provides a foundation for understanding the study's contributions and areas where it excels. Conversely, acknowledging limitations is equally essential. Any factors introducing bias, uncertainties, or reproducibility challenges should be openly declared. For instance, if the study relied on a specific patient population or limited sample size, these constraints should be communicated. The declaration of limitations extends to the robustness and generalizability of the results. If the study's outcomes are contingent on specific conditions, environments, or technologies, researchers must elucidate these dependencies. 

### References

{: .fs-2 }

1. 	Kocak B, Baessler B, Bakas S, et al (2023) CheckList for EvaluAtion of Radiomics research (CLEAR): a step-by-step reporting guideline for authors and reviewers endorsed by ESR and EuSoMII. Insights Imaging 14:75. https://doi.org/10.1186/s13244-023-01415-8
2. 	Guo M, Zang X, Fu W, et al (2023) Classification of nasal polyps and inverted papillomas using CT-based radiomics. Insights Imaging 14:188. https://doi.org/10.1186/s13244-023-01536-0
3. 	Gorodetski B, Becker PH, Baur ADJ, et al (2022) Inferring FDG-PET-positivity of lymph node metastases in proven lung cancer from contrast-enhanced CT using radiomics and machine learning. Eur Radiol Exp 6:44. https://doi.org/10.1186/s41747-022-00296-8
4. 	Sushentsev N, Rundo L, Blyuss O, et al (2021) MRI-derived radiomics model for baseline prediction of prostate cancer progression on active surveillance. Sci Rep 11:12917. https://doi.org/10.1038/s41598-021-92341-6


[Back](https://radiomic.github.io/CLEAR-E3/docs/Item2.html){: .btn .btn-purple .mr-5 }
[Next](https://radiomic.github.io/CLEAR-E3/docs/Item4.html){: .btn .btn-purple   }
