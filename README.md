# bank-marketing-data
# Bank Marketing Prediction

Machine learning and statistical analysis project based on the Bank Marketing dataset.

## Project objective

The objective of this project is to identify the factors that influence whether a bank client subscribes to a term deposit following a telemarketing campaign.

The project combines exploratory data analysis, data preprocessing and binary classification.

## Dataset

The dataset contains:

- 11,162 customer observations
- 17 explanatory variables
- Target variable: `deposit` (`yes` / `no`)
- Demographic, financial and campaign-related information

Source: Bank Marketing Dataset — UCI Machine Learning Repository / Kaggle.

## Project workflow

1. Data import
2. Statistical exploration
3. Data cleaning
4. Categorical variable encoding
5. Train-test split
6. Feature standardization
7. Model training
8. Model evaluation
9. Business interpretation

## Models

Two classification models were compared:

- Logistic Regression
- Random Forest

### Main results

| Metric | Logistic Regression | Random Forest |
|---|---:|---:|
| Accuracy | 0.809 | 0.823 |
| Precision | 0.808 | 0.792 |
| Recall | 0.785 | 0.851 |
| F1-score | 0.796 | 0.821 |
| ROC-AUC | 0.887 | 0.900 |

Random Forest achieved the best overall performance, particularly for recall, F1-score and ROC-AUC.

## Main insights

- Students and retired customers showed higher subscription rates.
- Customers with higher account balances subscribed more frequently.
- Call duration was strongly associated with subscription.
- Call duration should not be used alone for pre-call targeting because it is only known during or after the call.
- The model can support customer prioritization but should not be used as an automatic decision system.

## Files

- `bank_marketing_part_1.ipynb` — data exploration and preprocessing
- `bank_marketing_part_2.ipynb` — modelling and evaluation
- `bank_marketing_presentation.pdf` — project presentation

## Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## Author

Academic group project completed by:

- Marianna Manenkova
