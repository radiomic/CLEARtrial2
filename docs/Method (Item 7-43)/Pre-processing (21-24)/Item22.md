---
title: Item#22
layout: home
parent: Pre-processing (21-24)
grand_parent: Method (Item#7-43)
nav_order: 22
---

## CLEAR item#22


“Resampling method and its parameters. Specify the resampling technique (e.g., linear, cubic b-spline) applied to the pixels or voxels. Provide the physical pixel and voxel dimensions after resampling.” [1] (from [the article by Kocak et al.](https://insightsimaging.springeropen.com/articles/10.1186/s13244-023-01415-8); licensed under CC BY 4.0)


### Reporting examples for CLEAR item#22

> **Example#1.** “Voxel size resampling was performed before feature extraction using cubic and linear interpolation separately. Images were resampled to a voxel size of 3 × 3  ×  3 mm3; more information about the choice of voxel size can be found in the Supplementary Materials (Voxel size section).” [2] (from [the article by Casela et al.](https://doi.org/10.1016/j.ejrad.2021.109678); licensed under CC BY 4.0)

> **Example#2.** “In the phantom application, radiomics data from images without voxel resampling were extracted to study the impact of image resampling on radiomics data. For batch correction analysis, the images and masks were resampled to isometric voxels of 1 × 1 × 1 mm3 using spline interpolation and nearest-neighbor interpolation, respectively.” [3] (from [the article by Ligero et al.](https://doi.org/10.1007/s00330-020-07174-0); licensed under CC BY 4.0)

> **Example#3.** “Resampling was performed by a selection of four commonly image interpolation methods provided by SimpleITK and available in Pyradiomics. These methods included nearest neighbor, linear, Bspline and Blackman windowed-sinc interpolation” [4] (from [the article by Bleker et al.](https://doi.org/10.1002/jmri.28935); licensed under CC BY 4.0)

### Explanation and elaboration of CLEAR item#22

Item#22 emphasizes the importance of transparently reporting resampling methods and their further details. Radiomics features are sensitive to voxel size, and indeed variation in voxel size can impact feature robustness. Comparing voxels with different sizes can be troubling because it can introduce variability and inconsistency in the analysis. Therefore, standardizing voxel sizes is important to ensure the accuracy and consistency of radiomic analysis [5]. Models optimized with resampling techniques can outperform those without resampling [4]. This improvement may be attributed to  radiomic features sensitivity to heterogeneity in voxel spacing [6]. Some radiomics features could be voxel-size dependent which could be reduced with proper normalization [7]. Considering the dependency of feature values to resampling methods in multiple steps of the radiomic pipelines [8, 9], it is important to be transparent in reporting these details.   

### References

{: .fs-2 }

1. 	Kocak B, Baessler B, Bakas S, et al (2023) CheckList for EvaluAtion of Radiomics research (CLEAR): a step-by-step reporting guideline for authors and reviewers endorsed by ESR and EuSoMII. Insights Imaging 14:75. https://doi.org/10.1186/s13244-023-01415-8
2. 	Casale R, Lavrova E, Sanduleanu S, et al (2021) Development and external validation of a non-invasive molecular status predictor of chromosome 1p/19q co-deletion based on MRI radiomics analysis of Low Grade Glioma patients. Eur J Radiol 139:109678. https://doi.org/10.1016/j.ejrad.2021.109678
3. 	Ligero M, Jordi-Ollero O, Bernatowicz K, et al (2021) Minimizing acquisition-related radiomics variability by image resampling and batch effect correction to allow for large-scale data analysis. Eur Radiol 31:1460–1470. https://doi.org/10.1007/s00330-020-07174-0
4. 	Bleker J, Roest C, Yakar D, et al (2023) The Effect of Image Resampling on the Performance of Radiomics-Based Artificial Intelligence in Multicenter Prostate MRI. J Magn Reson Imaging JMRI. https://doi.org/10.1002/jmri.28935
5. 	Cattell R, Chen S, Huang C (2019) Robustness of radiomic features in magnetic resonance imaging: review and a phantom study. Vis Comput Ind Biomed Art 2:19. https://doi.org/10.1186/s42492-019-0025-6
6. 	Shafiq-ul-Hassan M, Latifi K, Zhang G, et al (2018) Voxel size and gray level normalization of CT radiomic features in lung cancer. Sci Rep 8:10545. https://doi.org/10.1038/s41598-018-28895-9
7. 	Paul R, Shafiq-Ul Hassan M, Moros EG, et al (2020) Deep Feature Stability Analysis Using CT Images of a Physical Phantom Across Scanner Manufacturers, Cartridges, Pixel Sizes, and Slice Thickness. Tomogr Ann Arbor Mich 6:250–260. https://doi.org/10.18383/j.tom.2020.00003
8. 	Kocak B, Yuzkan S, Mutlu S, et al (2023) Publications poorly report the essential RadiOmics ParametERs (PROPER): A meta-research on quality of reporting. Eur J Radiol 167:111088. https://doi.org/10.1016/j.ejrad.2023.111088
9. 	Koçak B, Yüzkan S, Mutlu S, et al (2023) Influence of image preprocessing on the segmentation-based reproducibility of radiomic features: in vivo experiments on discretization and resampling parameters. Diagn Interv Radiol Ank Turk. https://doi.org/10.4274/dir.2023.232543

[Back](https://radiomic.github.io/CLEAR-E3/docs/Method%20(Item%207-43)/Pre-processing%20(21-24)/Item21.html){: .btn .btn-purple .mr-5 }
[Next](https://radiomic.github.io/CLEAR-E3/docs/Method%20(Item%207-43)/Pre-processing%20(21-24)/Item23.html){: .btn .btn-purple   }
