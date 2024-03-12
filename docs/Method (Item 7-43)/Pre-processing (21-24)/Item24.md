---
title: Item#24
layout: home
parent: Pre-processing (21-24)
grand_parent: Method (Item#7-43)
nav_order: 24
---

## CLEAR item#24


“Image types (e.g., original, filtered, transformed). Provide the image types from which the radiomic features are extracted, e.g., original or images with convolutional filters (e.g., Laplacian of Gaussian edge enhancement, wavelet decomposition). Also, give nuances about the parameters of transformed image types (e.g., sigma values of Laplacian of Gaussian filtering).” [1] (from [the article by Kocak et al.](https://insightsimaging.springeropen.com/articles/10.1186/s13244-023-01415-8); licensed under CC BY 4.0)


### Reporting examples for CLEAR item#24

> **Example#1.** “Six kernel sizes of Laplacian of Gaussian (LoG) filters, 0.5, 1, 2, 3, 4 and 5 mm, were used to reconstruct the image, facilitating fine and coarse texture feature extraction at different resolutions.” [2] (from the article by Ching et al.; licensed under CC BY 4.0)

> **Example#2.** “In addition to the original-domain features, we extract several features from wavelet-derived images, namely higher-order features. They are extracted based on the first-order statistics and second-order textural features. These features are captured from the wavelet-domain images transformed by applying high (H) or low (L) filters in each of the three dimensions of the CT image. For the first level of wavelet decomposition, the filtering processing results in a total of 8 wavelet-filtered images: wavelet-LHL, wavelet-LHH, wavelet-HLL, wavelet-LLH, wavelet-HLH, wavelet-HHH, wavelet-HHL, and wavelet-LLL. Each wavelet-filtered image contributes 86 features (100 features excluding 14 shape features). Thus, one-level wavelet decomposition aggregates 688 radiomics features into the feature set. Higher-level wavelet decomposition further increases the number of radiomics features used for representing the hepatic lesions.” [3] (from the article by Tang et al.; licensed under CC BY 4.0)

### Explanation and elaboration of CLEAR item#24

Radiomics features can be extracted from various types of images, each potentially providing different information. Original images are unprocessed images as acquired from the medical imaging device, e.g., CT, MRI, PET-CT, and features extracted from these provide a baseline representation of the tissue or pathology without any enhancements or alterations. On the other hand, filtered images are the ones that have undergone processing using various filters to enhance certain characteristics or to remove noise. For example, Laplacian of Gaussian filters can be used for edge enhancement and wavelet decomposition could be used for breaking down the image into different frequency components, which can be useful for analyzing textures and patterns that are not visible in the original image [4]. This item also emphasizes the importance of detailing the parameters used in these transformations. For example, when using a Laplacian of Gaussian filter, the sigma value (which determines the spread of the Gaussian function) significantly affects the results of the edge enhancement and different sigma values can reveal different features or patterns in the image. 
### References

{: .fs-2 }

1. 	Kocak B, Baessler B, Bakas S, et al (2023) CheckList for EvaluAtion of Radiomics research (CLEAR): a step-by-step reporting guideline for authors and reviewers endorsed by ESR and EuSoMII. Insights Imaging 14:75. https://doi.org/10.1186/s13244-023-01415-8
2. 	Ching JCF, Lam S, Lam CCH, et al (2023) Integrating CT-based radiomic model with clinical features improves long-term prognostication in high-risk prostate cancer. Front Oncol 13:1060687. https://doi.org/10.3389/fonc.2023.1060687
3. 	Tang VH, Duong STM, Nguyen CDT, et al (2023) Wavelet radiomics features from multiphase CT images for screening hepatocellular carcinoma: analysis and comparison. Sci Rep 13:19559. https://doi.org/10.1038/s41598-023-46695-8
4. 	Depeursinge A, Andrearczyk V, Whybra P, et al (2023) Standardised convolutional filtering for radiomics. https://doi.org/10.48550/arXiv.2006.05470

[Back](https://radiomic.github.io/CLEAR-E3/docs/Method%20(Item%207-43)/Pre-processing%20(21-24)/Item23.html){: .btn .btn-purple .mr-5 }
[Next](https://radiomic.github.io/CLEAR-E3/docs/Method%20(Item%207-43)/Feature%20extraction%20(25-28)/Item25.html){: .btn .btn-purple   }
