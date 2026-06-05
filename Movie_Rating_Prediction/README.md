# Movie Rating Prediction Using Machine Learning

## Project Overview

Movie rating prediction is an important application of Machine Learning that helps estimate the likely rating of a movie based on various attributes such as genre, director, actors, duration, and audience engagement. Predicting movie ratings can assist viewers, content creators, and streaming platforms in understanding audience preferences and evaluating potential movie performance.

This project uses Machine Learning techniques to predict movie ratings based on real-world movie data. The project involves data preprocessing, feature engineering, exploratory data analysis, visualization, model training, and performance evaluation to identify the most effective regression model.

---

## Objectives

- Analyze factors that influence movie ratings.
- Perform Exploratory Data Analysis (EDA) using visualizations.
- Clean and preprocess real-world movie data.
- Apply feature engineering techniques to improve prediction performance.
- Build and compare multiple regression models.
- Evaluate model performance using regression metrics.
- Predict movie ratings based on movie characteristics.

---

## Dataset

The dataset contains important movie-related information used to predict ratings.

### Features

- **Genre** – Category of the movie.
- **Director** – Director of the movie.
- **Actors** – Lead actors featured in the movie.
- **Duration** – Runtime of the movie.
- **Votes** – Number of audience votes received.

### Target Variable

- **Rating** – Movie rating score.

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

## Data Preprocessing

Several preprocessing techniques were applied to prepare the dataset for Machine Learning:

- Handling missing values
- Cleaning duration and vote columns
- Removing inconsistent data
- Encoding categorical variables
- Log transformation of votes for improved distribution

---

## Feature Engineering

Additional feature engineering techniques were implemented to improve model performance:

- Extracting primary genre information
- Grouping less frequent directors into a common category
- Transforming numerical features for better learning

These techniques helped the model capture important patterns and improve prediction accuracy.

---

## Exploratory Data Analysis

The following visualizations were performed:

- Correlation Heatmap
- Actual vs Predicted Ratings Plot
- Feature Importance Graph

---

## Visualization Insights

The visualizations provided valuable insights into the factors affecting movie ratings. The correlation analysis helped identify relationships between numerical features and ratings, while the feature importance graph highlighted the variables that contributed most to prediction performance.

The Actual vs Predicted Ratings plot demonstrated how closely the model predictions matched the actual movie ratings, providing a clear assessment of model effectiveness. The analysis also showed that audience engagement, represented through vote counts, played a significant role in rating prediction.

Overall, the visualizations helped understand feature relationships, evaluate model performance, and identify the most influential factors affecting movie ratings.

---

## Machine Learning Models

The following regression models were trained and evaluated:

### Linear Regression

A baseline regression model used to establish initial prediction performance.

### Random Forest Regressor

An ensemble learning algorithm that combines multiple decision trees to improve prediction accuracy.

### Gradient Boosting Regressor

A boosting algorithm that sequentially improves prediction performance by correcting previous errors.

### XGBoost Regressor

An advanced gradient boosting algorithm known for its efficiency, speed, and predictive performance.

---

## Model Evaluation

The models were evaluated using standard regression metrics:

- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- R² Score

### Model Performance

Among all tested models, the XGBoost Regressor achieved the best overall performance.

- **R² Score:** 0.35
- **Root Mean Squared Error (RMSE):** 1.09

The results demonstrate the effectiveness of ensemble boosting techniques and feature engineering for predicting movie ratings using real-world movie data.

---

## Project Workflow

1. Data Collection
2. Data Cleaning
3. Exploratory Data Analysis
4. Data Visualization
5. Feature Engineering
6. Feature Selection
7. Model Training
8. Prediction
9. Model Evaluation
10. Model Comparison

---

## Key Insights

- Audience votes had a strong influence on movie ratings.
- Genre information significantly contributed to prediction performance.
- Director-related features played an important role in rating prediction.
- Feature engineering improved model stability and predictive capability.
- Ensemble learning techniques outperformed traditional regression models.
- XGBoost Regressor achieved the best overall performance among all tested models.

---

## Conclusion

This project successfully implemented a Movie Rating Prediction system using Machine Learning techniques in Python. The model was trained using movie-related features such as genre, director, duration, actors, and audience votes to predict movie ratings.

Exploratory Data Analysis and visualization techniques were used to understand feature relationships and identify important factors influencing movie ratings. Data preprocessing and feature engineering improved the quality of the dataset and enhanced model performance.

Multiple regression algorithms were evaluated, including Linear Regression, Random Forest Regressor, Gradient Boosting Regressor, and XGBoost Regressor. Among all models, the XGBoost Regressor achieved the best performance with an **R² Score of 0.35** and an **RMSE of 1.09**.

Overall, this project demonstrates how data preprocessing, visualization, feature engineering, and Machine Learning can be combined to solve real-world regression problems and generate meaningful insights from movie data.