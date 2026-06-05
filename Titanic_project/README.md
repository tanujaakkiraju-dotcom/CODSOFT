# Titanic Survival Prediction Using Machine Learning

## Project Overview

The Titanic disaster is one of the most well-known maritime tragedies in history. Predicting passenger survival based on demographic and travel-related information is a classic Machine Learning classification problem.

This project uses Machine Learning techniques to predict whether a passenger survived the Titanic disaster based on features such as age, gender, passenger class, fare, family information, and passenger titles. The project involves data preprocessing, exploratory data analysis, feature engineering, model training, and performance evaluation to identify the most effective prediction model.

---

## Objectives

- Analyze factors that influenced passenger survival.
- Perform Exploratory Data Analysis (EDA) using visualizations.
- Engineer new features to improve prediction accuracy.
- Build and compare multiple classification models.
- Evaluate model performance using classification metrics.
- Predict passenger survival based on historical data.

---

## Dataset

The dataset contains demographic and travel-related information of Titanic passengers.

### Features

- **Passenger Class (Pclass)** – Ticket class of the passenger.
- **Sex** – Gender of the passenger.
- **Age** – Age of the passenger.
- **SibSp** – Number of siblings/spouses aboard.
- **Parch** – Number of parents/children aboard.
- **Fare** – Ticket fare paid by the passenger.
- **Embarked** – Port of embarkation.
- **Title** – Passenger title extracted from names.
- **FamilySize** – Total family members aboard.
- **IsAlone** – Indicates whether a passenger traveled alone.

### Target Variable

- **Survived** – Indicates whether the passenger survived (1) or not (0).

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- XGBoost
- Jupyter Notebook
- VS Code

---

## Exploratory Data Analysis

The following visualizations were performed:

- Titanic Survival Count
- Survival Based on Gender
- Survival Based on Passenger Class
- Survival Based on Passenger Title



---

## Visualization Insights

The visualizations provided valuable insights into the factors that influenced passenger survival during the Titanic disaster. The survival count plot revealed the overall distribution of survivors and non-survivors within the dataset.

Gender-based analysis showed that female passengers had a significantly higher survival rate compared to male passengers. Passenger class analysis indicated that first-class passengers had better survival chances, while third-class passengers experienced lower survival rates.

The title-based survival analysis revealed that passenger titles such as Mrs and Miss were associated with higher survival probabilities compared to titles such as Mr. 

Overall, the visualizations highlighted important survival patterns and provided a deeper understanding of passenger demographics, travel class, and family-related factors that contributed to survival outcomes.

---

## Feature Engineering

Additional features were created to improve model performance:

- FamilySize
- IsAlone
- Passenger Title Extraction

These engineered features helped capture passenger relationships and travel behavior more effectively, improving predictive performance.

---

## Machine Learning Models

The following classification models were trained and evaluated:

### Logistic Regression

A baseline classification model used to establish initial prediction performance.

### Random Forest Classifier

An ensemble learning method that combines multiple decision trees to improve prediction accuracy and reduce overfitting.

### XGBoost Classifier

A gradient boosting algorithm known for its high performance and ability to handle complex feature interactions.

---

## Model Evaluation

The models were evaluated using classification performance metrics such as:

- Accuracy Score
- Precision
- Recall
- F1-Score
- Confusion Matrix

### Model Performance

Among all models, the XGBoost Classifier achieved the highest accuracy of **82.12%**, outperforming Logistic Regression and Random Forest Classifier.

The model successfully identified survival patterns by leveraging passenger demographics, family information, travel class, and engineered features.

---

## Key Insights

- Female passengers had a higher survival rate.
- First-class passengers had better survival chances.
- Third-class passengers experienced lower survival rates.
- Family relationships influenced survival probability.
- Passenger titles played an important role in predicting survival.
- Feature engineering significantly improved model performance.

---

## Conclusion

This project successfully implemented a Titanic Survival Prediction system using Machine Learning techniques in Python. The model was trained using passenger demographic and travel-related information to predict survival outcomes accurately.

Exploratory Data Analysis and visualization techniques were used to uncover important patterns and relationships within the dataset. The analysis revealed that factors such as gender, passenger class, family size, and passenger titles had a significant influence on survival probability.

Feature engineering techniques, including FamilySize, IsAlone, and Passenger Title Extraction, enhanced the predictive capability of the models. Multiple classification algorithms were evaluated, and the XGBoost Classifier achieved the highest accuracy of **82.12%**, demonstrating strong predictive performance.

Overall, this project showcases how data analysis, visualization, feature engineering, and Machine Learning can be combined to solve real-world classification problems and generate meaningful insights from historical data.