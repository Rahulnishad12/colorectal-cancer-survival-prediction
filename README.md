# colorectal-cancer-survival-prediction
Colorectal Cancer Survival &amp; Recurrence Prediction using Python and Machine Learning. Analyzed 89,945 patient records, performed data preprocessing and feature engineering, and developed two Logistic Regression classification models to evaluate survival status and cancer recurrence outcomes.

Colorectal Cancer Survival & Recurrence Prediction

Project Overview

This Data Analytics and Machine Learning project analyzes patient data to explore factors associated with colorectal cancer survival and recurrence outcomes.

Two separate Logistic Regression classification models were developed to predict Survival Status and Recurrence.

Dataset Overview

- Total Records: 89,945
- Total Columns: 30
- Missing Values: 0
- Duplicate Rows: 0
- Age Range: 20–89 years

Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Logistic Regression
- Jupyter Notebook

Data Preprocessing

- Excluded Patient_ID from model predictors.
- Applied median imputation and Standard Scaling to numerical features.
- Applied mode imputation and One-Hot Encoding to categorical features.
- Used an 80:20 stratified train-test split.
- Prevented direct target leakage by excluding both outcome columns from model inputs.

Machine Learning Models

1. Survival Status Classification
2. Recurrence Classification

Algorithm: Logistic Regression

Model Evaluation

Metric| Survival Status| Recurrence
Accuracy| 50.58%| 50.59%
Macro Precision| 50.42%| 50.39%
Macro Recall| 50.55%| 50.47%
Macro F1| 47.23%| 48.42%
ROC-AUC| 50.76%| 50.70%

Conclusion

This project demonstrates an end-to-end baseline Machine Learning workflow involving data preprocessing, classification and model evaluation.

The current model performance is close to random classification, indicating that further feature analysis, model improvement and external validation are needed.

Disclaimer

This project is for educational and research purposes only. It is not intended for clinical diagnosis, treatment decisions or individual patient care.