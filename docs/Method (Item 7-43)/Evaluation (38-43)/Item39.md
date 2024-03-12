---
title: Item#39
layout: home
parent: Evaluation (38-43)
grand_parent: Method (Item#7-43)
nav_order: 39
---

## CLEAR item#39


“Performance metrics and rationale for choosing. Specify the performance metrics to evaluate the predictive ability of the models. Justify the selected metrics according to the characteristics of the data (e.g., class imbalance). Beware of the potential pitfalls and follow recommendations when selecting the appropriate performance metrics.” [1] (from [the article by Kocak et al.](https://insightsimaging.springeropen.com/articles/10.1186/s13244-023-01415-8); licensed under CC BY 4.0)


### Reporting examples for CLEAR item#39

> **Example#1.** “Sensitivity, specificity, area under the receiver operating curve (AUC) were utilized to evaluate the model performance ability. Sensitivity and specificity of each model were determined at the optimal cutoff point on AUC, that is, the point where the Youden index (J = sensitivity + specificity−1) reaches its maximum.” [2] (from [the article by Feng et al.](https://doi.org/10.1186/s13244-023-01423-8); licensed under CC BY 4.0)

> **Example#2.** “The sensitivity, specificity, positive predictive value (PPV), negative predictive value (NPV) and Matthews correlation coefficient (MCC) for each model were calculated via a confusion matrix to evaluate discriminative ability. The MCC takes into account true positives, true negatives, false positives and false negatives, and is generally considered to be a well-balanced metric that can be applied even when the sample sizes of the two groups vary greatly.” [3] (from [the article by Xiong et al.](https://doi.org/10.21037/qims-22-599); licensed under CC BY-NC-ND 4.0)

> **Example#3.** “The difference of the calculated AUCs against chance was tested and considered significant if p ≤. 05. Cutoffs with high sensitivity (100%, C1; ≥ 95%, C2) were identified in the training dataset and then applied on the testing dataset to estimate the potential of the A.I. classifier to avoid unnecessary biopsies which equals the specificity because the patient population consisted only of suspicious biopsied findings. At the same time, the number of missed (false negative) cancers at these cutoffs could be determined.” [4] (from [the article by Pötsch et al.](https://doi.org/10.1007/s00330-021-07787-z); licensed under CC BY 4.0)

> **Example#4.** “[...]to estimate sensitivities, specificities, and predictive values of clinical prediction models, we dichotomized the outcome probability by using the median of the thresholds calculated in each imputed dataset in the development process to obtain a minimal desired specificity of 0.90 to select patients to avoid unnecessary hospitalizations/treatments” [5] (from [the article by Zysman et al.](https://doi.org/10.1007/s00330-023-09759-x); licensed under CC BY 4.0)



### Explanation and elaboration of CLEAR item#39

A multitude of performance metrics can be calculated and reported for various tasks such as detection, characterization, and prediction, depending on the type of output (binary, continuous, localization, etc.). Furthermore, the model output can be transformed from one type to another to determine widely used metrics (e.g., AUROC, sensitivity, specificity, etc.). Each metric describes distinct aspects of the model's performance and should, therefore, be chosen judiciously.  The choice of metrics should be  justified based on the model's task and output types, the class balance within the data [6], and published studies. The latter ensures a straightforward comparison with similar models. For instance, in the case of binary or multiclass output, confusion matrices should serve as the starting point for determining the desired metrics. When converting continuous output into dichotomous, it is imperative to clearly state the applied threshold used for the conversion.

### References

{: .fs-2 }

1. 	Kocak B, Baessler B, Bakas S, et al (2023) CheckList for EvaluAtion of Radiomics research (CLEAR): a step-by-step reporting guideline for authors and reviewers endorsed by ESR and EuSoMII. Insights Imaging 14:75. https://doi.org/10.1186/s13244-023-01415-8
2. 	Feng J, Zeng R, Geng Y, et al (2023) Automatic differentiation of ruptured and unruptured intracranial aneurysms on computed tomography angiography based on deep learning and radiomics. Insights Imaging 14:76. https://doi.org/10.1186/s13244-023-01423-8
3. 	Xiong X, Wang J, Ke J, et al (2023) Radiomics-based intracranial thrombus features on preoperative noncontrast CT predicts successful recanalization of mechanical thrombectomy in acute ischemic stroke. Quant Imaging Med Surg 13:68294–68694. https://doi.org/10.21037/qims-22-599
4. 	Pötsch N, Dietzel M, Kapetas P, et al (2021) An A.I. classifier derived from 4D radiomics of dynamic contrast-enhanced breast MRI data: potential to avoid unnecessary breast biopsies. Eur Radiol 31:5866–5876. https://doi.org/10.1007/s00330-021-07787-z
5. 	Zysman M, Asselineau J, Saut O, et al (2023) Development and external validation of a prediction model for the transition from mild to moderate or severe form of COVID-19. Eur Radiol 33:9262–9274. https://doi.org/10.1007/s00330-023-09759-x
6. 	García V, Mollineda RA, Sánchez JS (2010) Theoretical Analysis of a Performance Measure for Imbalanced Data. In: 2010 20th International Conference on Pattern Recognition. pp 617–620


[Back](https://radiomic.github.io/CLEAR-E3/docs/Method%20(Item%207-43)/Evaluation%20(38-43)/Item38.html){: .btn .btn-purple .mr-5 }
[Next](https://radiomic.github.io/CLEAR-E3/docs/Method%20(Item%207-43)/Evaluation%20(38-43)/Item40.html){: .btn .btn-purple   }
