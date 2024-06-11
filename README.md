# Loan-Defaulter-Detection-End-to-End-Pipeline
## Overview

This project aims to predict loan default using machine learning techniques. The dataset used in this project contains information about customers, their loan applications, and whether they defaulted on their loans. Various machine learning models are trained and evaluated to predict loan defaults accurately.

## Dataset

The dataset used in this project is obtained from `LoanDataset.csv`. It contains the following columns:

- `customer_age`: Age of the customer
- `customer_income`: Income of the customer
- `home_ownership`: Type of home ownership (e.g., RENT, OWN, MORTGAGE)
- `employment_duration`: Duration of employment in years
- `loan_intent`: Purpose of the loan (e.g., MEDICAL, EDUCATION, PERSONAL)
- `loan_grade`: Grade of the loan
- `loan_amnt`: Loan amount
- `loan_int_rate`: Loan interest rate
- `term_years`: Loan term in years
- `historical_default`: Historical default status
- `cred_hist_length`: Length of credit history
- `Current_loan_status`: Current loan status (target variable)

## Data Preprocessing

The dataset undergoes several preprocessing steps, including:

- Handling missing values
- Data cleaning (e.g., removing special characters, converting data types)
- Encoding categorical variables
- Scaling numeric features

## Model Training

Various machine learning models are trained on the preprocessed data, including:

- AdaBoost
- CatBoost
- Random Forest
- Decision Tree
- Logistic Regression
- LightGBM

The models are evaluated based on accuracy, precision, and F1-score.

## Results

`CatBoost` outperforms other models with an F1-score of 0.9856. Hyperparameter tuning is performed to optimize the CatBoost model further.

## Requirements

- Python 3.
- Libraries: pandas, numpy, seaborn, scikit-learn, catboost

## Usage

1. Clone the repository:

2. Install the required libraries:

```
pip install -r requirements.txt
```

3. Run the Jupyter notebook `Loan_Default_Prediction.ipynb` to reproduce the analysis and results.

## Contributors
- Mubashir Iqbal: [mubashiriqbal1221@gmail.com](mailto:mubashiriqbal1221@gmail.com)## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

--- 
