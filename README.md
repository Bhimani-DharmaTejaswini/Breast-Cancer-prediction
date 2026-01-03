# Breast Cancer Prediction Using Machine Learning

## Project Overview
Breast cancer is one of the most common cancers among women worldwide. Early and accurate detection plays a vital role in improving survival rates.  
This project uses **Machine Learning (Logistic Regression)** to classify breast tumors as **Malignant** or **Benign** using the **Breast Cancer Wisconsin (Diagnostic) Dataset**.

---

## Objective
- Understand and preprocess the dataset
- Build a classification model
- Predict whether a tumor is **Malignant (M)** or **Benign (B)**
- Evaluate model performance using accuracy and confusion matrix

---

## Dataset
- **Source:** Breast Cancer Wisconsin (Diagnostic) Dataset  
- **Target Variable:**  
  - `M` → Malignant  
  - `B` → Benign  

### Key Features:
- Radius
- Texture
- Perimeter
- Area
- Smoothness
- Compactness
- Concavity
- Concave points
- Symmetry
- Fractal Dimension

---

## Technologies Used
- Python
- Pandas
- NumPy
- Scikit-learn
- Logistic Regression

---

## Workflow
1. Load the dataset
2. Handle missing values (if any)
3. Encode categorical variables
4. Feature scaling
5. Train-test split
6. Train Logistic Regression model
7. Evaluate performance

---

### Logistic Regression
Logistic Regression is a supervised machine learning algorithm used for **binary classification**.  
It predicts the probability of a class using a sigmoid function and is efficient for medical diagnosis problems.

---

## Results
- High prediction accuracy
- Clear separation between malignant and benign tumors
- Reliable performance on unseen test data

---

## How to Run
```bash
pip install -r requirements.txt
cd src
python breast_cancer_prediction.py
