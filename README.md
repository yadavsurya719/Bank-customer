# Bank Customer Churn Model

This repository contains code for predicting customer churn in a bank using machine learning techniques.

## Overview

Customer churn is a critical metric for businesses, especially in the banking sector. This project aims to predict customer churn using various features such as credit score, geography, gender, age, tenure, balance, number of products, credit card status, active membership, and estimated salary.

## Dataset

The dataset used in this project is available in the file `Bank Churn Modelling.csv`. It contains information about 10,000 bank customers, including features and the churn label.

## Preprocessing

- Converted categorical variables like 'Geography' and 'Gender' into numerical format.
- Standardized numerical features using StandardScaler.
- Handled imbalanced data using random undersampling and random oversampling techniques.

## Modeling

- Utilized Support Vector Machine (SVM) classifier for modeling.
- Conducted hyperparameter tuning using GridSearchCV to improve model performance.

## Results

### Original Data

- Achieved an accuracy of 84% with SVM model.
- After hyperparameter tuning, the accuracy improved to 79%.

### Random Undersampling

- Achieved similar results as the original data with an accuracy of 79%.

### Random Oversampling

- Achieved similar results as the original data with an accuracy of 79%.

## Conclusion

- The SVM model showed reasonable performance in predicting customer churn.
- Random undersampling and oversampling techniques helped mitigate the class imbalance issue.
- Further exploration with different algorithms and feature engineering techniques could potentially improve model performance.
## License

This project is licensed under the [MIT License](LICENSE).

