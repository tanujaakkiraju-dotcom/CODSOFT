# Sales Prediction Using Multiple Linear Regression

## Project Overview

Sales prediction is an important task for businesses to estimate future product sales based on advertising expenditure. Accurate sales forecasting helps organizations optimize marketing budgets, improve decision-making, and maximize revenue.

This project uses Multiple Linear Regression to predict product sales based on advertising investments across different platforms such as TV, Radio, and Newspaper. The model analyzes the relationship between advertising expenditure and sales to generate accurate predictions.

---

## Objectives

- Analyze the relationship between advertising expenditure and product sales.
- Perform Exploratory Data Analysis (EDA) using data visualizations.
- Build a Multiple Linear Regression model for sales prediction.
- Evaluate model performance using regression metrics.
- Generate accurate sales forecasts based on advertising budgets.

---

## Dataset

The dataset contains advertising expenditure across different media platforms and corresponding sales figures.

### Features

- **TV** – Advertising budget spent on TV advertisements.
- **Radio** – Advertising budget spent on Radio advertisements.
- **Newspaper** – Advertising budget spent on Newspaper advertisements.

### Target Variable

- **Sales** – Product sales generated from advertising campaigns.

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook
- VS Code

---

## Exploratory Data Analysis

The following visualizations were performed:

- Correlation Heatmap
- Pairplot Analysis
- TV Advertising vs Sales Scatter Plot
- Radio Advertising vs Sales Scatter Plot
- Newspaper Advertising vs Sales Scatter Plot
- Actual vs Predicted Sales Comparison Graph

---

## Visualization Insights

The visualizations provided valuable insights into the relationship between advertising expenditure and product sales. The correlation heatmap showed that TV advertising has the strongest positive correlation with sales, indicating that it plays the most significant role in increasing product sales. Radio advertising also demonstrated a positive relationship with sales, while Newspaper advertising showed a comparatively weaker correlation.

The scatter plots further confirmed these relationships by displaying upward trends between advertising expenditure and sales, especially in the case of TV advertising. This suggests that higher spending on TV advertisements generally leads to increased sales performance. Radio advertising also contributes positively to sales, although its impact is moderate compared to TV advertising. On the other hand, Newspaper advertising exhibited a weaker linear pattern, indicating a smaller influence on sales prediction.

The pairplot visualization helped in understanding both the distribution of variables and the relationships among all features in the dataset. The plots showed patterns that are suitable for applying Multiple Linear Regression. Additionally, the Actual vs Predicted Sales graph demonstrated that the predicted sales values closely follow the actual sales values, indicating that the model performs effectively and provides accurate predictions.

Overall, the visualizations confirmed that advertising expenditure significantly affects product sales and validated the effectiveness of Multiple Linear Regression for sales prediction.

---

## Machine Learning Model

### Multiple Linear Regression

Multiple Linear Regression was used to model the relationship between advertising expenditure and sales.

The model predicts sales using the following independent variables:

- TV Advertising
- Radio Advertising
- Newspaper Advertising

---

## Model Evaluation

The model was evaluated using the following metrics:

- Mean Absolute Error (MAE) 
- Mean Squared Error (MSE)  
- Root Mean Squared Error (RMSE) 
- R² Score 

### Model Performance

## Model Evaluation

The performance of the Multiple Linear Regression model was evaluated using standard regression metrics, including Mean Absolute Error (MAE), Mean Squared Error (MSE), Root Mean Squared Error (RMSE), and R² Score.

**R² Score:** 0.90
**Root Mean Squared Error (RMSE):** 1.70


The model achieved a high level of prediction accuracy, with an R² Score of approximately 90.59%. The low error values indicate that the predicted sales values are very close to the actual sales values, demonstrating the reliability and effectiveness of the model for sales forecasting.



## Conclusion

This project successfully implemented a Sales Prediction system using Multiple Linear Regression in Python. The model was trained using advertising expenditure data from TV, Radio, and Newspaper platforms to predict product sales accurately.

Exploratory Data Analysis and visualization techniques were used to understand the relationship between advertising methods and sales performance. Among all advertising platforms, TV advertising showed the strongest impact on sales.

The model achieved an R² Score of 90.59%, indicating excellent prediction performance. The low error values such as MAE and RMSE also demonstrate that the model predictions are close to the actual sales values.

Overall, this project shows how Machine Learning can help businesses make data-driven decisions, optimize advertising budgets, and improve future sales forecasting.
```
