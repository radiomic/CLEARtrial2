## CLEAR item#21


“Image pre-processing details. Indicate which software programs or tools are used for pre-processing. Specify the version of the software and the exact configuration parameters. Provide reference and web link to the software, if available. Describe all pre-processing techniques and associated parameters applied to the image including the normalization (e.g., minimum–maximum normalization, standardization, logarithmic transformation, bias field correction), de-noising, skull stripping (also known as brain extraction), interpolation to create uniform images (e.g., in terms of slice thickness), standardized uptake value conversion, and registration. Also, state if an image or feature-based harmonization technique was used.” [1] (from [the article by Kocak et al.](https://insightsimaging.springeropen.com/articles/10.1186/s13244-023-01415-8); licensed under CC BY 4.0)


### Reporting examples for CLEAR item#21

> **Example#1.** “Preprocessing was performed with voxel resampling to 1 × 1 × 1 mm, whole-image gray level z-score normalization, scaling by a 100 factor and array shift (by 300), followed by discretization with a fixed bin width (= 5)”. [2] (from the article by Cuocolo et al.; licensed under CC BY 4.0)

> **Example#2.** “In the image pre-processing stage, we used B-spline interpolation resampling for image voxel size normalization, and all image sets were resampled to isotropic voxel size of 1 × 1 × 1 mm. Z-score intensity normalization was applied to reduce the impact of variability in image intensities on the stability of the radiomics features.” [3] (from the article by Chen et al.; licensed under CC BY 4.0)

### Explanation and elaboration of CLEAR item#21

Item#21 focuses on the pre-processing radiomics workflow. Radiomics features are affected by a large number of imaging valuables and acquisition parameters, including pixel size and slice thickness. Image pre-processing is needed to increase the reproducibility of the radiomics models in studies acquired with different techniques. It has been demonstrated that image normalization improves the reproducibility and performance of the radiomics models in retrospective studies [4, 5]. This is particularly relevant in retrospective or multicentric studies where images are acquired with different scanners or image protocols [6]. Several methods have been described for image pre-processing. Therefore, a description of the software with the exact parameters applied to the images is crucial for reproducible radiomics research [7]. 
### References

{: .fs-2 }

1. 	Kocak B, Baessler B, Bakas S, et al (2023) CheckList for EvaluAtion of Radiomics research (CLEAR): a step-by-step reporting guideline for authors and reviewers endorsed by ESR and EuSoMII. Insights Imaging 14:75. https://doi.org/10.1186/s13244-023-01415-8
2. 	Cuocolo R, Stanzione A, Faletti R, et al (2021) MRI index lesion radiomics and machine learning for detection of extraprostatic extension of disease: a multicenter study. Eur Radiol 31:7575–7583. https://doi.org/10.1007/s00330-021-07856-3
3. 	Chen Y, Qin S, Zhao W, et al (2023) MRI feature-based radiomics models to predict treatment outcome after stereotactic body radiotherapy for spinal metastases. Insights Imaging 14:169. https://doi.org/10.1186/s13244-023-01523-5
4. 	Foltyn-Dumitru M, Schell M, Rastogi A, et al (2023) Impact of signal intensity normalization of MRI on the generalizability of radiomic-based prediction of molecular glioma subtypes. Eur Radiol. https://doi.org/10.1007/s00330-023-10034-2
5. 	Park D, Oh D, Lee M, et al (2022) Importance of CT image normalization in radiomics analysis: prediction of 3-year recurrence-free survival in non-small cell lung cancer. Eur Radiol 32:8716–8725. https://doi.org/10.1007/s00330-022-08869-2
6. 	Liu X, Elbanan MG, Luna A, et al (2022) Radiomics in Abdominopelvic Solid-Organ Oncologic Imaging: Current Status. AJR Am J Roentgenol 219:985–995. https://doi.org/10.2214/AJR.22.27695
7. 	Wagner MW, Namdar K, Biswas A, et al (2021) Radiomics, machine learning, and artificial intelligence-what the neuroradiologist needs to know. Neuroradiology 63:1957–1967. https://doi.org/10.1007/s00234-021-02813-9

[Back](https://radiomic.github.io/CLEAR-E3/docs/Item2.html){: .btn .btn-purple .mr-5 }
[Next](https://radiomic.github.io/CLEAR-E3/docs/Item4.html){: .btn .btn-purple   }
