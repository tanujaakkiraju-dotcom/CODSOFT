# Iris Flower Classification

## Objective

The objective of this project is to build a machine learning model that can classify Iris flowers into different species based on their sepal and petal measurements. The model predicts whether a flower belongs to Iris Setosa, Iris Versicolor, or Iris Virginica.

---

## Dataset Used

The Iris Flower dataset was used for this project. It contains measurements of sepals and petals for three different Iris flower species.

Dataset Source: Kaggle Iris Flower Dataset

Features:
- Sepal Length
- Sepal Width
- Petal Length
- Petal Width

Target Variable:
- Species

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## Data Preprocessing

The following preprocessing techniques were applied:

- Removed duplicate rows
- Checked for missing values
- Dropped unnecessary columns
- Applied Label Encoding to categorical labels
- Performed Feature Scaling using StandardScaler

---

## Data Visualization

Several visualizations were used to analyze the dataset:

- Pairplot Visualization
- Correlation Heatmap
- Boxplot Visualization
- Confusion Matrix

These visualizations helped identify relationships between features and understand species distribution.

---

## Machine Learning Algorithm

The Random Forest Classifier was used for classification.

Reasons for selecting Random Forest:
- High classification accuracy
- Reduced overfitting compared to Decision Trees
- Effective handling of multiclass classification problems

---

## Model Evaluation

Model Accuracy:
- 96.67%

Cross Validation Scores:
- [0.9666, 0.9666, 0.9310, 0.8620, 1.0000]

Average Cross Validation Score:
- 94.53%

The high cross-validation score indicates that the model generalizes well to unseen data and shows minimal overfitting.

---

## Conclusion

The Random Forest Classifier successfully classified Iris flower species based on sepal and petal measurements. Data preprocessing, visualization, feature scaling, and cross-validation improved model performance and reliability.

The model achieved high accuracy and effectively distinguished between Iris Setosa, Iris Versicolor, and Iris Virginica species. This project demonstrates the complete machine learning workflow, including preprocessing, visualization, model training, evaluation, and performance validation using a multiclass classification dataset.

---