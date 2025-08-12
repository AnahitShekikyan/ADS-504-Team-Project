# **Predicting Student Academic Performance Using Machine Learning**

## **Project Overview**
This project applies supervised machine learning techniques to predict student academic performance using a dataset sourced from Kaggle. The dataset contains demographic, academic, and behavioral attributes for 10,000 students. The primary goal is to develop a model capable of accurately classifying student grades and identifying students who may be at risk of underperforming, enabling targeted interventions and support.

## **Objectives**
- Predict student academic performance based on demographic, academic, and engagement features.

- Identify at-risk students for early intervention.

- Compare the performance of multiple classification algorithms.

- Apply best practices in data preprocessing, class imbalance handling, and model evaluation.

## **Dataset**
- **Source:** [Student Performance Dataset – Kaggle](https://www.kaggle.com/datasets/bhuvaneshwarisa/student-performance-dataset)

- **Records:** 10,000

## **Features:**

- Demographics (gender, race/ethnicity, parental education)

- Academic scores (math, reading, writing, science)

- Other attributes (lunch status, test preparation course)

- Target Variable: Grade (A, B, C, D, Fail)

## **Methodology**
- Exploratory Data Analysis (EDA)

- Checked for missing values and duplicates.

- Visualized score distributions and correlations.

- Data Preprocessing

- Removed non-predictive identifiers.

- Imputed missing values using mean/median/mode.

- Label encoded categorical variables.

- Applied SMOTE to address class imbalance.

- Standardized features for applicable models.

## **Modeling**

- Logistic Regression (Baseline)

- Random Forest

- XGBoost

- Evaluation Metrics

- Accuracy

- Macro- and Weighted-average F1 Scores

- ROC Curves & AUC

## **Results**
- Model	Accuracy	Macro F1	Weighted F1
- Random Forest	99.9%	0.9987	0.9990
- XGBoost	99.4%	0.9895	0.9940
- Logistic Regression	58.3%	0.5623	0.5979

### **Best Model:** 
Random Forest

## **Key Insight:** 
Tree-based algorithms with SMOTE handling excelled in both accuracy and class balance.

## **Conclusion**
Random Forest achieved the best performance across all evaluation metrics, proving highly effective in predicting academic performance and identifying at-risk students. This predictive approach can be used by educators to inform interventions, improve outcomes, and support data-driven decision-making.

## **Note:** 
This project uses Python 3.9+ and the following key libraries: pandas, numpy, matplotlib, seaborn, scikit-learn, xgboost, and imblearn.

## References

1. [Bhuvaneshwari. (2023). *Student performance dataset*. Kaggle.](https://www.kaggle.com/datasets/bhuvaneshwarisa/student-performance-dataset)  
2. Chawla, N. V., Bowyer, K. W., Hall, L. O., & Kegelmeyer, W. P. (2002). *SMOTE: Synthetic Minority Over-sampling Technique*. *Journal of Artificial Intelligence Research*, 16, 321–357. [https://doi.org/10.1613/jair.953](https://doi.org/10.1613/jair.953)  
3. Géron, A. (2019). *Hands-On Machine Learning with Scikit-Learn, Keras, and TensorFlow* (2nd ed.). O’Reilly Media.  
4. Romero, C., & Ventura, S. (2020). *Educational data mining and learning analytics: An updated survey*. *Wiley Interdisciplinary Reviews: Data Mining and Knowledge Discovery*, 10(3), e1355. [https://doi.org/10.1002/widm.1355](https://doi.org/10.1002/widm.1355)  

