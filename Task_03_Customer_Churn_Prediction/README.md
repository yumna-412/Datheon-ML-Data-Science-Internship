# Customer Churn Prediction Using Ensemble Learning

## Project Overview

This project implements an ensemble machine learning classification pipeline using the Telco Customer Churn dataset. Two machine learning algorithms, Random Forest and XGBoost, are trained and evaluated to predict whether a telecom customer is likely to leave the service.

## Dataset

- **Dataset:** Telco Customer Churn Dataset
- **Total Records:** 7,043
- **Features:** Customer demographics, account information, and subscription services.
- **Target:** Churn
- **Classes:** Yes, No

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- XGBoost
- Imbalanced-learn
- Jupyter Notebook

## Project Workflow

1. Load and explore the Telco Customer Churn dataset.
2. Check missing values and dataset distribution.
3. Convert TotalCharges into numeric format and handle missing values.
4. Encode categorical features using OneHotEncoder.
5. Split the dataset into training and testing data.
6. Handle class imbalance using SMOTE.
7. Train Random Forest and XGBoost classifiers.
8. Perform cross-validation to evaluate model performance.
9. Evaluate both models using accuracy, precision, recall, F1-score, and ROC-AUC.
10. Generate classification reports and confusion matrices.
11. Plot ROC curves to compare model performance.
12. Extract and visualize the top 10 important features.

## Model Performance

| Metric | Random Forest | XGBoost |
|---|---:|---:|
| Accuracy | 76.37% | 77.08% |
| Precision | 54.37% | 56.12% |
| Recall | 68.18% | 62.57% |
| F1-Score | 60.50% | 59.17% |
| ROC-AUC | 83.55% | 83.71% |

### Cross-Validation Results

| Model | Mean CV ROC-AUC |
|---|---:|
| Random Forest | 84.03% |
| XGBoost | 84.01% |

Both models achieved ROC-AUC scores above the target of 80%.

### Feature Importance

The feature importance analysis identified the following important factors associated with customer churn:

- Contract type (Month-to-month)
- Customer tenure
- Internet service type (Fiber optic)
- Online security
- Payment method (Electronic check)
- Tech support
- Total charges

## Conclusion

This project demonstrates an ensemble machine learning approach for predicting customer churn. Random Forest and XGBoost models were compared using multiple evaluation metrics, cross-validation, and ROC-AUC analysis.

XGBoost achieved the highest test ROC-AUC score of 83.71%, while Random Forest achieved a higher churn recall of 68.18%.

Feature importance analysis helped identify key factors associated with customer churn. Both models successfully exceeded the target ROC-AUC score of 80%.

## Project Files

- `Telco-Customer-Churn.csv` – Dataset used for customer churn prediction.
- `Customer_Churn_Prediction.ipynb` – Notebook containing the complete implementation.
- `README.md` – Project documentation.