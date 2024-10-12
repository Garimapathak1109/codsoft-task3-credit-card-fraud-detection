# codsoft-task3-credit-card-fraud-detection
# Credit Card Fraud Detection Project

## Project Overview

This project aims to detect fraudulent transactions in a credit card dataset. Given the challenge of handling imbalanced data (where fraudulent cases are far fewer than non-fraudulent ones), two machine learning models—**Random Forest Classifier** and **Logistic Regression**—were used to predict fraud. The **SMOTE** technique was applied to handle class imbalance, improving the models' ability to identify fraud.

## Conclusion of the Credit Card Fraud Detection Model

### 1. Handling Class Imbalance:
- The dataset was imbalanced, with significantly fewer fraud cases.
- **SMOTE** (Synthetic Minority Over-sampling Technique) was utilized to balance the dataset, generating synthetic samples for the minority class.

### 2. Model Performance:
- **Random Forest Classifier** (non-linear) performed better at detecting fraud, capturing complex patterns.
- **Logistic Regression** (linear model) was not as effective in identifying the relationships between features.

### 3. Evaluation Metrics:
- **Confusion matrices**, **classification reports**, and **accuracy scores** were used to evaluate model performance.
- **Random Forest** showed stronger results in detecting fraud.
- **Precision-Recall** and **ROC curves** provided insights into the balance between precision, recall, and false positives.

### 4. Visualizations:
- Confusion matrices and curves helped visualize the strengths and weaknesses of the models.
- **Random Forest** was more capable of handling complex fraud detection scenarios compared to Logistic Regression.

## Summary:
- **Random Forest** is the superior model for this task, given its ability to handle non-linear relationships and the complexities of fraud detection.
- **Logistic Regression** serves as a good baseline but lacks the depth needed for advanced fraud detection.
- **SMOTE** was effective in addressing class imbalance, enhancing model performance.
