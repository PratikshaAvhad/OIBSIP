# Credit Card Fraud Detection

**Internship:** Oasis Infobyte Data Analytics Internship  
**Level:** Level 2  
**Task:** Credit Card Fraud Detection

## Objective
To analyze credit card transactions and build machine learning models to identify potentially fraudulent transactions.

## Tools and Technologies
- Python
- Pandas and NumPy
- Matplotlib and Seaborn
- Scikit-learn
- Jupyter Notebook

## Project Workflow
1. Dataset loading and data cleaning
2. Exploratory Data Analysis (EDA)
3. Train-test splitting
4. Logistic Regression model training
5. Random Forest model training
6. Model evaluation and comparison
7. Feature importance analysis

## Model Results

| Metric | Logistic Regression | Random Forest |
|---|---:|---:|
| Accuracy | 96.51% | 99.95% |
| Fraud Precision | 4.09% | 97.10% |
| Fraud Recall | 88.42% | 70.53% |
| Fraud F1-score | 7.82% | 81.71% |

## Dataset
The dataset file `creditcard.csv` is not included in this repository because of its large size. Download the dataset from its original source and place it in the same folder as the notebook before running the code.

## Files
- `Fraud_Detection.ipynb` — Jupyter Notebook containing analysis and models
- `ss/` — Project screenshots
- `README.md` — Project documentation

## Conclusion
This project compares Logistic Regression and Random Forest for credit card fraud detection. Random Forest achieved higher precision and F1-score, while Logistic Regression achieved higher fraud recall. The results demonstrate why multiple evaluation metrics are important for imbalanced datasets.
