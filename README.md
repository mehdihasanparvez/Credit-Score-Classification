# Credit Score Classification Using Machine Learning

## Project Overview
This project focuses on predicting customer credit scores using Machine Learning techniques. It analyzes financial and credit-related information to classify customers into three categories: **Good, Standard, and Poor**.

The project includes data preprocessing, exploratory data analysis (EDA), feature engineering, model training, hyperparameter tuning, and model evaluation.

## Dataset Information
- **Total Records:** 100,000
- **Total Features:** 28
- **Target Variable:** Credit_Score
- **Classification Type:** Multiclass Classification

### Key Features
- Customer Age and Occupation
- Annual Income and Monthly Salary
- Number of Bank Accounts and Credit Cards
- Interest Rate and Loan Information
- Delayed Payments
- Outstanding Debt
- Credit Utilization Ratio
- Credit History Age
- Monthly Balance

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- XGBoost
- Jupyter Notebook

## Machine Learning Models
The following models were trained and evaluated:

1. Random Forest Classifier
2. XGBoost Classifier

Hyperparameter tuning was performed to improve model performance.

## Model Performance

| Model | Validation Accuracy | Macro F1-Score |
|---|---:|---:|
| Tuned Random Forest | 79.42% | 0.7872 |
| Tuned XGBoost | **80.98%** | **0.7997** |

### Best Model: XGBoost

- **Validation Accuracy:** 80.98%
- **Validation Macro F1-Score:** 0.7997

XGBoost achieved the best overall performance among the evaluated models.

## Project Workflow
1. Data Loading
2. Data Cleaning and Preprocessing
3. Handling Missing Values
4. Exploratory Data Analysis (EDA)
5. Feature Engineering
6. Categorical Encoding
7. Train and Validation Split
8. Model Training
9. Hyperparameter Tuning
10. Model Evaluation and Comparison
##csv file link
https://drive.google.com/file/d/14LvM6F8gk-yCGkc-Ng0DY0MifhxL-EjF/view?usp=drive_link
https://drive.google.com/file/d/1AqhESMy544qEoQnArfGQ-rDo_SryAmK-/view?usp=drive_link
## Results
The XGBoost model achieved 80.98% validation accuracy and a macro F1-score of 0.7997. These results demonstrate the potential of machine learning techniques for credit score classification.

## Conclusion
This project demonstrates how machine learning can be used to analyze customer financial data and predict credit scores. Among the tested models, XGBoost provided the best classification performance.

## Author
**Parvez Hasan**

Computer Science Student | Machine Learning Enthusiast
