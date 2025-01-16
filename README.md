# Logistic Regression Project

## Project Overview
This project implements a logistic regression model from scratch using **NumPy** to classify breast cancer tumors as malignant or benign. The goal is to understand the basics of machine learning by implementing a simple model without relying on high-level libraries.

## Dataset
The dataset used is **data.csv**, which contains information about tumor characteristics. Key columns include:

- **diagnosis**: Target variable (M = Malignant, B = Benign).
- **radius_mean**, **texture_mean**, **area_mean**, etc.: Features describing tumor characteristics.
- **Unnamed: 32**: An irrelevant column removed during preprocessing.

## Steps in the Project
1. **Data Loading and Preprocessing**:
   - Loaded the dataset using Pandas.
   - Removed irrelevant columns.
   - Encoded the target variable (`M` = 1, `B` = 0).
   - Normalized the features for better performance.

2. **Logistic Regression Implementation**:
   - Implemented the sigmoid function.
   - Used binary cross-entropy as the loss function.
   - Optimized model weights using gradient descent.

3. **Evaluation**:
   - Calculated the accuracy of the model.

## Results
- The model successfully classifies tumors as malignant or benign.
- **Accuracy**: Replace with computed value.

## How to Run
1. Place the "Breast Cancer Wisconsin .ipynb" notebook and "data.csv" in the same directory.
2. Open the notebook in Jupyter Notebook.
3. Execute the cells step by step to view the results.

---

This was a beginner-level project to learn logistic regression from scratch. Future improvements could include splitting the data into training and testing sets, incorporating advanced evaluation metrics like precision and recall, or experimenting with other machine learning models.

