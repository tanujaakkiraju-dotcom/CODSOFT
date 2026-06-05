# Credit Card Fraud Detection Using Random Forest Classifier

## Project Overview

Credit card fraud detection is one of the most important applications of machine learning in the financial sector. With the rapid growth of digital transactions, detecting fraudulent activities accurately and efficiently has become essential for reducing financial losses and ensuring customer security.

This project uses a Random Forest Classifier to identify fraudulent credit card transactions based on transaction features. The dataset is highly imbalanced, with fraudulent transactions representing only a small percentage of the total records. To address this challenge, SMOTE (Synthetic Minority Oversampling Technique) was applied to balance the dataset and improve the model's ability to detect fraud.

The project demonstrates the complete machine learning workflow, including data preprocessing, handling class imbalance, visualization, model training, evaluation, and performance validation.

---

## Objectives

- Analyze credit card transaction data to identify fraud patterns.
- Perform Exploratory Data Analysis (EDA) using visualizations.
- Handle class imbalance using SMOTE.
- Build a Random Forest Classification model.
- Evaluate model performance using classification metrics.
- Identify important features contributing to fraud detection.

---

## Dataset

The dataset contains credit card transactions made by European cardholders.

### Features

- **Time** – Time elapsed between transactions.
- **Amount** – Transaction amount.
- **V1 to V28** – Anonymized numerical features obtained through PCA transformation.

### Target Variable

- **Class** – Transaction category:
  - 0 = Genuine Transaction
  - 1 = Fraudulent Transaction

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Imbalanced-learn (SMOTE)
- Jupyter Notebook
- VS Code

---

## Data Preprocessing

The following preprocessing steps were performed:

- Checked for missing values
- Examined class distribution
- Scaled Time and Amount features using StandardScaler
- Split the dataset into training and testing sets
- Applied SMOTE to balance the training data
- Prepared feature and target variables for model training

---

## Exploratory Data Analysis

The following visualizations were performed:

- Fraud vs Genuine Transaction Distribution Analysis
- Confusion Matrix Analysis
- Feature Importance Analysis
- Actual vs Predicted Fraud Transaction Analysis

---

## Visualization Insights

The visualizations provided valuable insights into both the dataset and the performance of the fraud detection model. The class distribution plot revealed a highly imbalanced dataset, with genuine transactions significantly outnumbering fraudulent transactions. This highlighted the importance of applying SMOTE to balance the classes and improve the model's ability to identify fraudulent activities effectively.

The confusion matrix showed that the Random Forest model correctly classified the majority of both genuine and fraudulent transactions, with only a small number of misclassifications. The feature importance plot identified the most influential transaction features used by the model, indicating that certain variables play a significant role in distinguishing fraudulent activities from legitimate transactions.

The Actual vs Predicted Fraud Transactions visualization demonstrated that the predicted fraud count closely matched the actual fraud count, confirming the model's ability to learn and recognize fraud patterns accurately. Overall, the visualizations validated the effectiveness of the preprocessing techniques and highlighted the strong performance of the Random Forest model in fraud detection.

---

## Machine Learning Model

### Random Forest Classifier

The Random Forest Classifier was used to classify transactions as genuine or fraudulent.

The model predicts transaction classes using the following independent variables:

- Time
- Amount
- V1 to V28 Features

---

## Model Evaluation

The model was evaluated using the following techniques:

- Accuracy Score
- Precision Score
- Recall Score
- F1 Score
- Classification Report
- Confusion Matrix

### Model Performance

The Random Forest Classifier achieved an Accuracy of approximately **99.95%**, demonstrating excellent performance in distinguishing between genuine and fraudulent transactions.

The model achieved a Precision score of approximately **85.26%**, indicating that most transactions classified as fraudulent were correctly identified. The Recall score of approximately **82.65%** shows that the model successfully detected a large proportion of actual fraudulent transactions. The F1 Score of approximately **83.94%** reflects a strong balance between precision and recall.

These results confirm that the model effectively identifies fraudulent transactions while minimizing false alarms and missed fraud cases.

---

## Conclusion

This project successfully implemented a Credit Card Fraud Detection system using the Random Forest Classifier in Python. The model was trained on transaction data and enhanced using SMOTE to address the issue of class imbalance.

Exploratory Data Analysis and visualization techniques were used to understand transaction patterns and model behavior. The visualizations highlighted the severe class imbalance in the dataset and demonstrated the importance of balancing techniques for improving fraud detection performance.

The model achieved an Accuracy of **99.95%**, a Precision score of **85.26%**, a Recall score of **82.65%**, and an F1 Score of **83.94%**, demonstrating strong predictive performance and reliable fraud detection capability.

Overall, this project highlights the effectiveness of machine learning techniques in financial fraud detection and demonstrates the complete workflow of data preprocessing, class balancing, visualization, model training, evaluation, and validation using a real-world fraud detection dataset.
```
