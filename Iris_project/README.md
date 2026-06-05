# Iris Flower Classification Using Random Forest Classifier

## Project Overview

The Iris Flower Classification project is a machine learning classification task that aims to identify and classify Iris flowers into their respective species based on sepal and petal measurements. The three species included in the dataset are Iris Setosa, Iris Versicolor, and Iris Virginica.

This project uses the Random Forest Classifier to learn patterns from flower measurements and accurately predict the species of unseen Iris flowers. The project demonstrates the complete machine learning workflow, including data preprocessing, visualization, model training, evaluation, and performance validation.

---

## Objectives

- Analyze the characteristics of different Iris flower species.
- Perform Exploratory Data Analysis (EDA) using visualizations.
- Apply data preprocessing and feature scaling techniques.
- Build a Random Forest Classification model.
- Evaluate model performance using classification metrics.
- Validate model reliability using Cross Validation.

---

## Dataset

The dataset contains measurements of Iris flowers from three different species.

### Features

- **Sepal Length** – Length of the sepal in centimeters.
- **Sepal Width** – Width of the sepal in centimeters.
- **Petal Length** – Length of the petal in centimeters.
- **Petal Width** – Width of the petal in centimeters.

### Target Variable

- **Species** – Iris flower species:
  - Iris Setosa
  - Iris Versicolor
  - Iris Virginica

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

## Data Preprocessing

The following preprocessing steps were performed:

- Checked for missing values
- Removed duplicate records
- Dropped unnecessary columns
- Applied Label Encoding to the target variable
- Performed Feature Scaling using StandardScaler
- Split the dataset into training and testing sets

---

## Exploratory Data Analysis

The following visualizations were performed:

- Pairplot Visualization
- Correlation Heatmap
- Boxplot Visualization
- Confusion Matrix

---

## Visualization Insights

The visualizations provided valuable insights into the relationships and distribution of features within the Iris dataset. The pairplot showed that petal measurements are highly effective in distinguishing between the three Iris species, with Iris Setosa being clearly separated from the other species. Iris Versicolor and Iris Virginica displayed slight overlap but remained distinguishable through petal-related features.

The correlation heatmap revealed a strong positive correlation between petal length and petal width, indicating that these features increase together and play a significant role in species classification. Sepal measurements showed comparatively weaker correlations.

The boxplot visualization highlighted the variation in petal length among the three species. Iris Setosa exhibited the smallest petal lengths, while Iris Virginica had the largest values. Iris Versicolor occupied the intermediate range, further confirming the importance of petal measurements for classification.

The confusion matrix demonstrated that the model correctly classified the majority of flower samples, with very few misclassifications. Overall, the visualizations confirmed that petal-related features are the most influential factors in accurately classifying Iris flower species.

---

## Machine Learning Model

### Random Forest Classifier

The Random Forest Classifier was used to classify Iris flowers into their respective species.

The model predicts flower species using the following independent variables:

- Sepal Length
- Sepal Width
- Petal Length
- Petal Width

---

## Model Evaluation

The model was evaluated using the following techniques:

- Accuracy Score
- Classification Report
- Confusion Matrix
- Cross Validation

### Model Performance

The Random Forest Classifier achieved an accuracy of approximately **96.67%**, demonstrating excellent classification performance on unseen data.

Cross-validation was performed to assess model stability and generalization capability. The model achieved an average cross-validation score of approximately **94.53%**  indicating consistent performance across different data splits and minimal overfitting.

The high accuracy and cross-validation scores confirm that the model effectively learned the distinguishing characteristics of each Iris flower species.

---

## Conclusion

This project successfully implemented an Iris Flower Classification system using the Random Forest Classifier in Python. The model was trained using sepal and petal measurements to accurately classify flowers into Iris Setosa, Iris Versicolor, and Iris Virginica species.

Exploratory Data Analysis and visualization techniques were used to understand feature relationships and species distributions. The visualizations revealed that petal length and petal width are the most important features for distinguishing between Iris species.

The model achieved an accuracy of 96.67% and an average cross-validation score of 94.53%, demonstrating excellent predictive performance and strong generalization capability.

Overall, this project highlights the effectiveness of machine learning classification techniques and demonstrates the complete workflow of data preprocessing, visualization, model training, evaluation, and validation using a real-world multiclass classification dataset.