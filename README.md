# Decision Tree Classification

## Objective

The objective of this project is to build a Decision Tree Classification model, analyze its performance, optimize its hyperparameters, and interpret the rules and important features learned by the model.

## Project Overview

This project follows the complete machine learning workflow, including data preparation, exploratory data analysis, feature engineering, model building, hyperparameter tuning, and model evaluation.

## Tasks Performed

### 1. Data Preparation
- Loaded the dataset using Pandas.
- Examined the structure and dimensions of the dataset.
- Checked data types and data quality.

### 2. Exploratory Data Analysis (EDA)
- Analyzed summary statistics.
- Checked for missing values.
- Identified potential outliers and inconsistencies.
- Visualized feature distributions using:
  - Histograms
  - Box plots
  - Correlation matrix
- Analyzed relationships between features.

### 3. Feature Engineering
- Handled missing values where required.
- Encoded categorical variables.
- Prepared features for machine learning.
- Applied appropriate preprocessing techniques.

### 4. Decision Tree Classification
- Split the dataset into training and testing sets.
- Built a Decision Tree Classification model using Scikit-learn.
- Trained the model using the training dataset.
- Generated predictions on the testing dataset.

### 5. Model Evaluation
The model was evaluated using:

- Accuracy
- Precision
- Recall
- F1-Score
- ROC-AUC
- Confusion Matrix

### 6. Hyperparameter Tuning
Different Decision Tree hyperparameters were experimented with to improve model performance, including:

- `max_depth`
- `min_samples_split`
- `min_samples_leaf`
- `criterion`

Hyperparameter tuning was performed to reduce overfitting and obtain a better-performing model.

### 7. Decision Tree Visualization
The trained Decision Tree was visualized to understand:

- The decision-making process
- Splitting conditions
- Classification rules
- Important features

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook / Google Colab

## Project Structure

```text
Decision-Tree-Classification/
│
├── Decision_Tree_Classification.ipynb
├── dataset.csv
└── README.md
