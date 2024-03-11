## CLEAR item#37


“Model selection strategy. Describe how the final model was selected. Two broad categories for these are probabilistic (e.g., Akaike information criterion, Bayesian information criterion) and resampling methods (e.g., random train-test split, cross-validation, bootstrap validation). Clearly state that only the training and validation sets are used for model selection. State if the model complexity is considered in selection, for instance, the “one standard error rule”. Specify which performance metrics were used to select the final model.”  [1] (from [the article by Kocak et al.](https://insightsimaging.springeropen.com/articles/10.1186/s13244-023-01415-8); licensed under CC BY 4.0)


### Reporting examples for CLEAR item#37

> **Example#1.** “When the “one-standard error” rule was used, FAE produced a simpler model with eight features, […]” [2] (from the article by Chen et al.; licensed under CC BY 4.0)

> **Example#2.** “We performed hyperparameter optimization in order to select the best configuration for each method (LR, SVM, RF, and XGBoost) in terms of AUC, using Grid Search. The search was integrated into the repeated 5-fold cross-validation with bootstrap bias correction and used bootstrap sampling of the pooled predictions from all the 5 folds, separately for each task. […] We finally chose the optimized model with the highest AUC among included models to be used in the ensemble model, which was evaluated on an independent test set.” [3] (from the article by Woźnicki et al.; licensed under CC BY 4.0)

> **Example#3.** “We utilized filtered features to construct logistic regression (LR), random forest (RF), and support vector machine (SVM) models. LR was chosen as the classifier for subsequent model building due to its superior generalization performance. Based on the combination of 3 types of features (radiomics, DL, and radiomics + DL as the hybrid feature) in different regions, 9 imaging models were constructed to verify the prediction effect of different types of features and ROI regions on ATRX mutation status, and the image models were named according to the combination of feature types (i.e., radiomics, DL, hybrid) and feature source (i.e., edema, tumor, overall). The optimal imaging model was selected according to the average AUC of the models with 5-fold cross-validation.” [4] (from the article by Liu et al.; licensed under CC BY-NC-ND 4.0)

> **Example#4.** “To select the best-performing model, a cross-validation (CV) strategy has been adopted, in which 4 folds (training a stratified 5-fold cross-set) were iteratively used to train a model that was subsequently tested on the left-out fold (test set). During the CV, all the combinations of FS and classifiers were evaluated. The parameters of the models were tuned, and models not reaching a mean area under the receiver operating characteristic (ROC) curve (AUC) ≥ 0.6 on the left-out folds were discarded.” [5] (from the article by Nicoletti et al.; licensed under CC BY 4.0)

> **Example#5.** A backward stepwise multivariable logistic regression was performed using the Akaike information criterion (AIC) as the stop rule.” [6] (from the article by Fang et al.; licensed under CC BY 4.0)

### Explanation and elaboration of CLEAR item#37

Item#37 addresses the critical aspect of model selection strategy. Authors are advised to explicitly detail how the final model was chosen. This involves providing insights into the specific criteria or metrics used for selection, whether it be through probabilistic indicators or resampling techniques. While the literature often presents the selection of algorithms as somewhat arbitrary, adopting a best practice involves choosing an algorithm based on the outcomes of multiple experiments [7]. It is imperative that authors explicitly mention the utilization of only the training and validation sets in the model selection process to maintain the integrity of the evaluation process. Furthermore, authors should clarify whether they account for model complexity, such as with the "one standard error rule" [8]. This rule is a commonly used criterion in model selection, suggesting that the simplest model within one standard error of the optimal performance should be chosen, helping to find a balance between model complexity and performance. Finally, specifying the performance metrics used for selecting the final model in a radiomics study guarantees transparency and comparability. Various examples are provided above to exemplify different selection strategies and level of details.

### References

{: .fs-2 }

1. 	Kocak B, Baessler B, Bakas S, et al (2023) CheckList for EvaluAtion of Radiomics research (CLEAR): a step-by-step reporting guideline for authors and reviewers endorsed by ESR and EuSoMII. Insights Imaging 14:75. https://doi.org/10.1186/s13244-023-01415-8
2. 	Chen C, Qin Y, Chen H, et al (2022) Machine learning to differentiate small round cell malignant tumors and non-small round cell malignant tumors of the nasal and paranasal sinuses using apparent diffusion coefficient values. Eur Radiol 32:3819–3829. https://doi.org/10.1007/s00330-021-08465-w
3. 	Woźnicki P, Westhoff N, Huber T, et al (2020) Multiparametric MRI for Prostate Cancer Characterization: Combined Use of Radiomics Model with PI-RADS and Clinical Parameters. Cancers 12:1767. https://doi.org/10.3390/cancers12071767
4. 	Liu Z, Xu X, Zhang W, et al (2024) A fusion model integrating magnetic resonance imaging radiomics and deep learning features for predicting alpha-thalassemia X-linked intellectual disability mutation status in isocitrate dehydrogenase–mutant high-grade astrocytoma: a multicenter study. Quant Imaging Med Surg 14:25163–25263. https://doi.org/10.21037/qims-23-807
5. 	Nicoletti G, Mazzetti S, Maimone G, et al (2024) Development and Validation of an Explainable Radiomics Model to Predict High-Aggressive Prostate Cancer: A Multicenter Radiomics Study Based on Biparametric MRI. Cancers 16:203. https://doi.org/10.3390/cancers16010203
6. 	Fang J, Sun W, Wu D, et al (2022) Value of texture analysis based on dynamic contrast-enhanced magnetic resonance imaging in preoperative assessment of extramural venous invasion in rectal cancer. Insights Imaging 13:179. https://doi.org/10.1186/s13244-022-01316-2
7. 	Koçak B, Durmaz EŞ, Ateş E, Kılıçkesmez Ö (2019) Radiomics with artificial intelligence: a practical guide for beginners. Diagn Interv Radiol Ank Turk 25:485–495. https://doi.org/10.5152/dir.2019.19321
8. 	Hastie T, Tibshirani R, Friedman J (2009) The Elements of Statistical Learning. Springer, New York, NY


[Back](https://radiomic.github.io/CLEAR-E3/docs/Item2.html){: .btn .btn-purple .mr-5 }
[Next](https://radiomic.github.io/CLEAR-E3/docs/Item4.html){: .btn .btn-purple   }
