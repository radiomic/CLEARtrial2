---
title: Item#36
layout: home
parent: Modeling (34-37)
grand_parent: Method (Item#7-43)
nav_order: 36
---

## CLEAR item#36


“Handling of confounders. Describe the method (e.g., directed acyclic graphs) for the detection of potential confounders (e.g., differences in tumor size between cohorts, different image acquisition parameters such as slice thickness, and differences in patient populations between primary and secondary hospitals). Please also describe how confounding was addressed (e.g., covariate adjustment).” [1] (from [the article by Kocak et al.](https://insightsimaging.springeropen.com/articles/10.1186/s13244-023-01415-8); licensed under CC BY 4.0)


### Reporting examples for CLEAR item#36

> **Example#1.** “We used multivariable linear regression to investigate relationships between meat intake and cardiovascular phenotypes, adjusting for confounders (age, sex, deprivation, educational level, smoking, alcohol intake, exercise) and potential covariates on the causal pathway (hypertension, hypercholesterolaemia, diabetes, body mass index).” [2] (from the article by Raisi-Estabragh et al.; licensed under CC BY 4.0)

> **Example#2.** “[…] a variety of MRI acquisition protocols and equipment of different vendors were used. Although this may impact the radiomics analyses, it reflects current clinical routine. Ideally, a correlation analyses would be performed of test-retest data from different vendors and magnetic field strengths to standardize the data, but such datasets are not available. Instead, multivariate analysis of variance (MANOVA) was performed to compare the mean factor scores between vendors and magnetic field strength in VUMC patient cohorts. In the UMCU cohorts (OSCC and OPSCC), only the mean factor scores between magnetic field strengths were compared, because most scans were obtained using one MR vendor […]” [3] (from the article by Mes et al.; licensed under CC BY 4.0)

> **Example#3.** “The main CT scan parameter in this cohort that affected (was associated with) radiomics features values was the CT scan slice thickness (among other parameters including CT scan voltage (kVp), vender and reconstruction algorithm). Because this is a multi-institutional cohort with different imaging protocols, we aimed to remove the potentially confounding effect of slice thickness from the radiomics signature to be built. […] In this project, we aimed to build a radiomics signature that deliver new prognostic information, independent of tumor size which has long been known as an important prognosticator. The correlation between tumor size and the radiomics features were measured by Pearson’s linear correlation coefficients (also called Pearson’s R). In our study, tumor size was obtained by measuring the longest diameter across the tumor’s cross-sectional region, as shown in Figure 1. The features that have strong positive or negative correlation with tumor size (Pearson’s R >0.7 or <−0.7, p < 0.05) were excluded from radiomics signature model #4 as tumor size dependent features. […] a direct association between confounding factors and survival outcomes was also studied. The two confounding factors were CT slice thickness and tumor size. The information of CT slice thickness was retrieved from DICOM attributes tagged as (0018,0050). Patients were assigned to two subgroups with slice thickness ≤3 mm (74 patients) and >3 mm (109 patients). With respect to tumor size, patients were assigned to two subgroups with tumor size less than or equal to the median size value (60 patients) and greater than the median value (123 patients).” [4] (from the article by Lu et al.; licensed under CC BY 4.0)

> **Example#4.** “The differences before and after therapy for the parameters of volume, MPP, uniformity, BMI, and serum protein level were tested with the paired-samples t-test (two-sided). Cohen’s d with Hedges’ correction was used as the effect size parameter. For further mechanistic analyses, the differences after therapy minus before therapy were calculated for these data and subjected to bivariate parametric correlation analyses and variance analysis. In addition, for the radiomic parameters, the results of the paired t-tests were adjusted for the effect of BMI difference by including BMI difference as a covariate." [5] (from the article by Santer et al.; licensed under CC BY 4.0)

### Explanation and elaboration of CLEAR item#36

Item#36 is instructing researchers to describe how they identified and managed confounders in their study. Confounders are factors that could potentially influence both the dependent and independent variables, creating a false association or hiding a real one [6, 7]. To address confounders, authors can use several statistical techniques such as covariate adjustment, where researchers control for the potential confounders in their analyses, ensuring that the relationship they observe between the independent variables (e.g., radiomic features) and the dependent variable (e.g., treatment outcome) is not due to these confounding factors. Unfortunately, radiomic studies can be confounded by a variety of factors like tumor size and acquisition parameters such as slice thickness [4]. Detection and control of these potential confounders is required for reliable and clinically useful radiomic models.

### References

{: .fs-2 }

1. 	Kocak B, Baessler B, Bakas S, et al (2023) CheckList for EvaluAtion of Radiomics research (CLEAR): a step-by-step reporting guideline for authors and reviewers endorsed by ESR and EuSoMII. Insights Imaging 14:75. https://doi.org/10.1186/s13244-023-01415-8
2. 	Raisi-Estabragh Z, McCracken C, Gkontra P, et al (2021) Associations of Meat and Fish Consumption With Conventional and Radiomics Cardiovascular Magnetic Resonance Phenotypes in the UK Biobank. Front Cardiovasc Med 8:
3. 	Mes SW, van Velden FHP, Peltenburg B, et al (2020) Outcome prediction of head and neck squamous cell carcinoma by MRI radiomic signatures. Eur Radiol 30:6311–6321. https://doi.org/10.1007/s00330-020-06962-y
4. 	Lu L, Ahmed FS, Akin O, et al (2021) Uncontrolled Confounders May Lead to False or Overvalued Radiomics Signature: A Proof of Concept Using Survival Analysis in a Multicenter Cohort of Kidney Cancer. Front Oncol 11:
5. 	Santer M, Riechelmann H, Hofauer B, et al (2023) Radiomic Assessment of Radiation-Induced Alterations of Skeletal Muscle Composition in Head and Neck Squamous Cell Carcinoma within the Currently Clinically Defined Optimal Time Window for Salvage Surgery—A Pilot Study. Cancers 15:4650. https://doi.org/10.3390/cancers15184650
6. 	Zhao Q, Adeli E, Pohl KM (2020) Training confounder-free deep learning models for medical applications. Nat Commun 11:6010. https://doi.org/10.1038/s41467-020-19784-9
7. 	Badgeley MA, Zech JR, Oakden-Rayner L, et al (2019) Deep learning predicts hip fracture using confounding patient and healthcare variables. Npj Digit Med 2:1–10. https://doi.org/10.1038/s41746-019-0105-1



[Back](https://radiomic.github.io/CLEAR-E3/docs/Method%20(Item%207-43)/Modeling%20(34-37)/Item35.html){: .btn .btn-purple .mr-5 }
[Next](https://radiomic.github.io/CLEAR-E3/docs/Method%20(Item%207-43)/Modeling%20(34-37)/Item37.html){: .btn .btn-purple   }
