## CLEAR item#17


“Definition of non-radiomic predictor variables. Describe the data elements appearing as non-radiomic predictors. Non-radiomic variables might be demographic characteristics (e.g., age, gender, ethnicity), widely used traditional laboratory biomarkers (e.g., carcinoembryonic antigen), or traditional approaches used in daily clinical practice (e.g., radiologist’s qualitative reading, Hounsfield Unit evaluation, Response Evaluation Criteria in Solid Tumors [RECIST], Response Assessment in Neuro-Oncology [RANO] criteria). It would be helpful to know how these predictors were identified (e.g., based on a literature review). If applicable, describe any transformation of predictors (e.g., binarization of continuous predictors, the grouping of levels of categorical variables).”  [1] (from [the article by Kocak et al.](https://insightsimaging.springeropen.com/articles/10.1186/s13244-023-01415-8); licensed under CC BY 4.0)


### Reporting examples for CLEAR item#17

> **Example#1.** “Patients’ clinicopathological information was acquired from the hospital information system at each study center. Clinical information includes patients’ age, body mass index (BMI), menopausal status, prior treatment history, combination regimen with ICIs, lines of previous therapy in the context of metastatic disease, hematologic indicators, blood biochemical indices, and tumor metastatic burden. Pathological information included tumor pathological type, (estrogen receptor progesterone receptor and HER2 status), Ki67 proliferation index, and PD-L1 expression status.” [2] (from the article by Zhao et al.; licensed under CC BY-NC 4.0)

> **Example#2.** “Clinical data, including the patient age at diagnosis, date of surgery, type and grade of tumor, the international federation of obstetricians and gynecologists (FIGO) stage, presence of lymphovascular space invasion, and any adjuvant or neoadjuvant treatment of these subjects were obtained from an online medical records system.” [3] (from the article by Li et al.; licensed under CC BY 4.0)

### Explanation and elaboration of CLEAR item#17

As previously recommended in a seminal paper from Lambin et al. published back in 2017, non-radiomics variables should be considered for the feature selection phase of radiomics modeling to create holistic models [4]. The importance of non-radiomic variables or approaches has been recently emphasized in METRICS as well [5]. Indeed, it appears entirely reasonable that those parameters of already recognized and reliable clinical value in the specific study context should be taken into account. Furthermore, they often represent the starting point as well as the benchmark against which radiomics must measure itself. Radiomics should ideally integrate into the clinical workflow by enhancing it and not necessarily replacing it. Similar to radiologists considering relevant clinical-laboratory data when interpreting images, a radiomic predictive model should also consider parameters of interest beyond the quantitative ones derived from the images, which potentially includes radiologic subjective assessment when appropriate. In both examples, details about the collection of clinical data as non-radiomic features were given in detail, which were further used in the sole or integrated analyses in the source papers. 

### References

{: .fs-2 }

1. 	Kocak B, Baessler B, Bakas S, et al (2023) CheckList for EvaluAtion of Radiomics research (CLEAR): a step-by-step reporting guideline for authors and reviewers endorsed by ESR and EuSoMII. Insights Imaging 14:75. https://doi.org/10.1186/s13244-023-01415-8
2. 	Zhao J, Sun Z, Yu Y, et al (2023) Radiomic and clinical data integration using machine learning predict the efficacy of anti-PD-1 antibodies-based combinational treatment in advanced breast cancer: a multicentered study. J Immunother Cancer 11:e006514. https://doi.org/10.1136/jitc-2022-006514
3. 	Li X, Marcus D, Russell J, et al (2023) An Integrated Clinical-MR Radiomics Model to Estimate Survival Time in Patients With Endometrial Cancer. J Magn Reson Imaging 57:1922–1933. https://doi.org/10.1002/jmri.28544
4. 	Lambin P, Leijenaar RTH, Deist TM, et al (2017) Radiomics: the bridge between medical imaging and personalized medicine. Nat Rev Clin Oncol 14:749–762. https://doi.org/10.1038/nrclinonc.2017.141
5. 	Kocak B, Akinci D’Antonoli T, Mercaldo N, et al (2024) METhodological RadiomICs Score (METRICS): a quality scoring tool for radiomics research endorsed by EuSoMII. Insights Imaging. https://doi.org/10.1186/s13244-023-01572-w


[Back](https://radiomic.github.io/CLEAR-E3/docs/Item2.html){: .btn .btn-purple .mr-5 }
[Next](https://radiomic.github.io/CLEAR-E3/docs/Item4.html){: .btn .btn-purple   }
