---
title: Item#23
layout: home
parent: Pre-processing (21-24)
grand_parent: Method (Item#7-43)
nav_order: 23
---

## CLEAR item#23


“Discretization method and its parameters. Specify the discretization method (e.g., fixed bin width, fixed bin count method, or histogram equalization) used for hand-crafted radiomic feature extraction. Report the rationale for using a particular discretization technique. Indicate the number of gray levels for the fixed bin count method or the bin width as well as the value of the first level (or minimum and maximum bounds) for the fixed bin width method. Any experimental detail with different discretization methods and values is important to declare.”  [1] (from [the article by Kocak et al.](https://insightsimaging.springeropen.com/articles/10.1186/s13244-023-01415-8); licensed under CC BY 4.0)


### Reporting examples for CLEAR item#23

> **Example#1.** “In this volume of interest (VOI), intensities of FDG uptake were resampled with an absolute method of 64 discrete values and bounds set to 0 and 30 SUV values, corresponding to the typical range of tumor SUVs encountered in GEJC.” [2] (from [the article by Amrane  et al.](https://doi.org/10.1038/s41598-023-31587-8); licensed under CC BY 4.0)

> **Example#2.** “Voxel intensities were aggregated into 25 bins of Hounsfield Units to reduce noise and inter-scanner variability.” [3] (from [the article by Refaee et al.](https://doi.org/10.3389/fmed.2022.915243); licensed under CC BY 4.0)

### Explanation and elaboration of CLEAR item#23

Discretization plays a central role in radiomics studies. By reducing the impact of noise, it enhances the robustness and reliability of image analysis. Since discretization largely affects downstream analyses, it is important to choose adequate bin width or bin number and to use the same discretization methods consistently across the whole patients’ cohort [4, 5]. It is not clear yet whether absolute (fixed bin width) or relative (fixed bin number) discretization should be preferred, although it has been reported that in case of images with definite gray values (e.g., SUV in PET imaging, HU in CT) absolute discretization (fixed bin width) yield more reproducible results [6, 7]. Whatever discretization method is adopted, it must be reported transparently [8, 9].

### References

{: .fs-2 }

1. 	Kocak B, Baessler B, Bakas S, et al (2023) CheckList for EvaluAtion of Radiomics research (CLEAR): a step-by-step reporting guideline for authors and reviewers endorsed by ESR and EuSoMII. Insights Imaging 14:75. https://doi.org/10.1186/s13244-023-01415-8
2. 	Amrane K, Thuillier P, Bourhis D, et al (2023) Prognostic value of pre-therapeutic FDG-PET radiomic analysis in gastro-esophageal junction cancer. Sci Rep 13:5789. https://doi.org/10.1038/s41598-023-31587-8
3. 	Refaee T, Salahuddin Z, Frix A-N, et al (2022) Diagnosis of Idiopathic Pulmonary Fibrosis in High-Resolution Computed Tomography Scans Using a Combination of Handcrafted Radiomics and Deep Learning. Front Med 9:915243. https://doi.org/10.3389/fmed.2022.915243
4. 	Papp L, Rausch I, Grahovac M, et al (2019) Optimized Feature Extraction for Radiomics Analysis of 18F-FDG PET Imaging. J Nucl Med Off Publ Soc Nucl Med 60:864–872. https://doi.org/10.2967/jnumed.118.217612
5. 	Orlhac F, Nioche C, Klyuzhin I, et al (2021) Radiomics in PET Imaging:: A Practical Guide for Newcomers. PET Clin 16:597–612. https://doi.org/10.1016/j.cpet.2021.06.007
6. 	Leijenaar RTH, Nalbantov G, Carvalho S, et al (2015) The effect of SUV discretization in quantitative FDG-PET Radiomics: the need for standardized methodology in tumor texture analysis. Sci Rep 5:11075. https://doi.org/10.1038/srep11075
7. 	van Timmeren JE, Cester D, Tanadini-Lang S, et al (2020) Radiomics in medical imaging—“how-to” guide and critical reflection. Insights Imaging 11:91. https://doi.org/10.1186/s13244-020-00887-2
8. 	Kocak B, Yuzkan S, Mutlu S, et al (2023) Publications poorly report the essential RadiOmics ParametERs (PROPER): A meta-research on quality of reporting. Eur J Radiol 167:111088. https://doi.org/10.1016/j.ejrad.2023.111088
9. 	Koçak B, Yüzkan S, Mutlu S, et al (2023) Influence of image preprocessing on the segmentation-based reproducibility of radiomic features: in vivo experiments on discretization and resampling parameters. Diagn Interv Radiol Ank Turk. https://doi.org/10.4274/dir.2023.232543



[Back](https://radiomic.github.io/CLEAR-E3/docs/Method%20(Item%207-43)/Pre-processing%20(21-24)/Item22.html){: .btn .btn-purple .mr-5 }
[Next](https://radiomic.github.io/CLEAR-E3/docs/Method%20(Item%207-43)/Pre-processing%20(21-24)/Item24.html){: .btn .btn-purple   }
