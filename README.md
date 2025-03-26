# Leveraging Machine Learning Approaches for Breast Cancer Prediction 

This repository contains a machine learning project focused on predicting Brest Cancer using various algorithms, including Random Forest, Decision Tree, SVM, Logistic Regression and K-Nearest Neighbors (KNN).

# About the Dataset

This dataset will be used for training and evaluating classification algorithms in the field of Supervised Machine Learning. The primary objective is to develop a predictive model capable of classifying tumors as either Malignant (M) or Benign (B) based on a variety of input features.

**Total Records:** 569 samples

**Total Features:** 33 columns (including diagnosis and measurement features)

## Class Distribution:

**Benign (B):** 357 instances

**Malignant (M):** 212 instances

This dataset serves as a valuable resource for exploring techniques in classification, feature selection, and model evaluation.

## Download the Dataset

To obtain the dataset, follow one of the methods below:

### 1. From GitHub Website

- Navigate to the `datasets` directory within this repository.
- Click on the dataset CSV file (e.g., `breast_cancer_dataset`).
- Once opened, click on the **Download** button (or right-click on **Raw** and select **Save Link As...**) to save it locally.

### 2. Using Git Command Line

- Clone the repository:
  ```bash
  git clone https://github.com/yourusername/Breast-Cancer-Dataset.git
- The dataset CSV file (e.g., breast_cancer_dataset.csv) will be available in this directory.

### Example Code to Load the Dataset

To load the CSV dataset into your Python script using pandas, use the following code snippet:
```bash
import pandas as pd

# Load the dataset
df = pd.read_csv('breast_cancer_dataset.csv')

# Display the first few rows
print(df.head())


