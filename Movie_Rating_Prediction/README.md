# Movie Rating Prediction Using Machine Learning

This project uses Machine Learning techniques to predict movie ratings based on features such as genre, director, duration, actors, and audience votes. The project focuses on data preprocessing, feature engineering, exploratory data analysis, and regression modeling using real-world movie data.

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* XGBoost

## Dataset Features

The dataset contains important movie-related information including:

* Genre
* Director
* Actors
* Duration
* Votes
* Movie Ratings

## Data Preprocessing

Several preprocessing techniques were applied to clean and prepare the dataset for machine learning:

* Handling missing values
* Cleaning duration and vote columns
* Converting categorical data into numerical format
* Removing inconsistent values
* Log transformation of votes for better distribution

## Feature Engineering

Additional feature engineering techniques were used to improve model performance:

* Extracting primary genre information
* Grouping less frequent directors into a common category
* Transforming numerical features for better learning

## Exploratory Data Analysis

Various visualizations were created to better understand the dataset and model performance:

* Correlation Heatmap
* Actual vs Predicted Ratings Plot
* Feature Importance Graph

These visualizations helped identify relationships between features and movie ratings while evaluating model effectiveness.

## Machine Learning Models Used

The following regression algorithms were explored and compared:

* Linear Regression
* Random Forest Regressor
* Gradient Boosting Regressor
* XGBoost Regressor

Among all tested models, the XGBoost Regressor achieved the best overall performance.

## Final Model Performance

The final XGBoost model achieved:

* **R² Score:** 0.34
* **Root Mean Squared Error (RMSE):** 1.10

The results demonstrate the effectiveness of ensemble boosting techniques and feature engineering for predicting movie ratings using real-world movie data.

## Project Workflow

1. Data Collection
2. Data Cleaning
3. Exploratory Data Analysis
4. Feature Engineering
5. Feature Selection
6. Model Training
7. Prediction
8. Model Evaluation
9. Model Comparison

## Key Insights

* Audience votes had a strong influence on movie ratings.
* Genre and director information contributed significantly to prediction performance.
* Feature engineering and preprocessing improved model stability and accuracy.
* XGBoost Regressor performed better than other tested regression models.

## Conclusion

This project successfully demonstrates a complete Machine Learning workflow for regression problems using movie rating data. Through preprocessing, feature engineering, visualization, and advanced regression algorithms, the model was able to predict movie ratings while providing meaningful insights into the factors influencing audience and critic ratings.
