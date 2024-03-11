## CLEAR item#30


“Details of class imbalance. Indicate the balance status of the classes according to the reference standard. Provide details about how class imbalance is handled. Specify the techniques (e.g., synthetic minority over-sampling, simple over-sampling through replication, under-sampling) used to achieve the class balance. Clearly state these data augmentation and under-sampling strategies are applied only in the training set.” [1] (from [the article by Kocak et al.](https://insightsimaging.springeropen.com/articles/10.1186/s13244-023-01415-8); licensed under CC BY 4.0)


### Reporting examples for CLEAR item#30

> **Example#1.** “Given the unbalanced condition for all molecular predictors […] an iterative way of K-fold cross-validation was applied. This method made sure that among the possible combinations of data splitting, only those one having the number of minority class subjects at least equal to half of the number of majority class were included among the eligible reshuffles.” [2] (from the article by Pasquini et al.; licensed under CC BY 4.0)

> **Example#2.** “A balanced distribution of the target molecular mutation is ensured in the training and testing sets in each molecular prediction model.” [3] (from the article by Shboul et al.; licensed under CC BY 4.0)

> **Example#3.** “Data category imbalance may cause the results of the model to be skewed toward the category with more data and reduce the reliability of the model. To address this problem, we used the synthetic minority oversampling technique (SMOTE), which increases the sample of minority categories.” [4] (from the article by Li et al.; licensed under CC BY 4.0)

### Explanation and elaboration of CLEAR item#30

When working with machine learning techniques, it is important that the different classes are balanced. Nevertheless, some diseases have inherently low incidence rates. While training a model, particularly if training with resampling occurs, a potential dataset imbalance should be addressed. A common technique is represented by oversampling the minority class data with mathematical methods, such as the synthetic minority over-sampling technique (SMOTE) [5]. To obtain clinically meaningful and representative performance metric values, it is particularly important not to alter the native class balance (i.e., prevalence or epidemiological representation) of the test sets. It should also be noted that not all models are equally affected by class imbalance.

### References

{: .fs-2 }

1. 	Kocak B, Baessler B, Bakas S, et al (2023) CheckList for EvaluAtion of Radiomics research (CLEAR): a step-by-step reporting guideline for authors and reviewers endorsed by ESR and EuSoMII. Insights Imaging 14:75. [https://doi.org/10.1186/s13244-023-01415-8](https://doi.org/10.1186/s13244-023-01415-8)
2. 	Wang S, Zhu C, Jin Y, et al (2023) A multi-model based on radiogenomics and deep learning techniques associated with histological grade and survival in clear cell renal cell carcinoma. Insights Imaging 14:207. [https://doi.org/10.1186/s13244-023-01557-9](https://doi.org/10.1186/s13244-023-01557-9)
3. 	Hirvasniemi J, Klein S, Bierma-Zeinstra S, et al (2021) A machine learning approach to distinguish between knees without and with osteoarthritis using MRI-based radiomic features from tibial bone. Eur Radiol 31:8513–8521. [https://doi.org/10.1007/s00330-021-07951-5](https://doi.org/10.1007/s00330-021-07951-5)

[Back](https://radiomic.github.io/CLEAR-E3/docs/Item2.html){: .btn .btn-purple .mr-5 }
[Next](https://radiomic.github.io/CLEAR-E3/docs/Item4.html){: .btn .btn-purple   }
