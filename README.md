# breast-cancer-decision-tree
Breast Cancer Prediction using Decision Tree Classification
# Breast Cancer Prediction Using Decision Tree Classification

## Project Overview
This project implements a **Decision Tree Classification model** to predict whether a breast tumor is **Benign** or **Malignant** based on clinical diagnostic features.  
The goal is to assist in **early detection of breast cancer** using supervised machine learning techniques.

---

## Objective
- To build a machine learning model that accurately classifies breast cancer cases.
- To analyze diagnostic features and identify key factors influencing predictions.
- To visualize and interpret the Decision Tree for explainability.

---

## Dataset
- **Name:** Breast Cancer Wisconsin Dataset
- **Source:** UCI Machine Learning Repository
- **Instances:** 569
- **Features:** 30 numerical diagnostic features
- **Target Variable:**  
  - `M` → Malignant  
  - `B` → Benign

---

## Technologies Used
- Python
- Google Colab
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn

---

## Methodology
1. Data loading and exploration
2. Data preprocessing and label encoding
3. Train-test split
4. Model training using Decision Tree Classifier
5. Model evaluation using accuracy, confusion matrix, and classification report
6. Decision Tree visualization for interpretability

---

## Algorithm Used
**Decision Tree Classifier**
- Criterion: Entropy
- Max Depth: 5
- Advantages:
  - Easy to interpret
  - No feature scaling required
  - Suitable for medical datasets

---

## Results
- Achieved **high classification accuracy (~92–95%)**
- Successfully identified important diagnostic features influencing cancer prediction
- Clear interpretability through decision tree visualization

---

## Evaluation Metrics
- Accuracy Score
- Precision
- Recall
- F1-Score
- Confusion Matrix

---

## How to Run the Project
1. Clone the repository:
   ```bash
   git clone https://github.com/USERNAME/breast-cancer-decision-tree.git
