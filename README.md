# Customer-and-Market-Analysis

## Project Overview
This repository contains three machine learning projects showcasing various supervised and unsupervised learning techniques. Each project focuses on data preprocessing, feature engineering, model training, evaluation, and visualization.

---

## File Structure
- **`data/`**: Contains the datasets used in each project.
- **`scripts/`**: Python scripts implementing the machine learning models.
- **`outputs/`**: Saved figures, evaluation metrics, and results.

---

## Projects

### 1. Predict Customer Churn
This project predicts whether a customer will churn using a Random Forest Classifier.

- **Dataset**: `Telco-Customer-Churn.csv`
- **Steps**:
  - Preprocess the data by handling missing values and encoding categorical variables.
  - Train a Random Forest classifier.
  - Evaluate the model using accuracy, confusion matrix, and ROC curve.
- **Results**:
  - **Accuracy**: 79.84%
  - Confusion Matrix and ROC Curve are included in the `outputs/` folder.

---

### 2. Predict Housing Prices
This project predicts housing prices using a Random Forest Regressor.

- **Dataset**: `AmesHousing.csv`
- **Steps**:
  - Preprocess data with log transformation and feature selection based on correlation.
  - Train a Random Forest Regressor with optimized hyperparameters.
  - Evaluate the model using Mean Squared Error (MSE) and R² Score.
- **Results**:
  - **Mean Squared Error (MSE)**: 0.0191
  - **R² Score**: 89.69%
  - Visualization: True vs Predicted Sale Prices (Scatter Plot).

---

### 3. Customer Segmentation
This project uses K-Means clustering to segment customers based on spending patterns and demographics.

- **Dataset**: `Mall_Customers.csv`
- **Steps**:
  - Perform data scaling and encoding.
  - Use the Elbow Method to determine the optimal number of clusters (k=5).
  - Visualize customer clusters in a scatter plot.
- **Results**:
  - **Elbow Method** shows the optimal k at 5 clusters.
  - Scatter plot visualizes customer segments by age and spending score.
