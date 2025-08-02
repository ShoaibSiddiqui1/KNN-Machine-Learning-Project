# KNN-Machine-Learning-Project
Breakthrough Tech AI Program

# 🧠 Income Classification with K-Nearest Neighbors (KNN)

This project was completed as part of my Break Through Tech AI Program ML Foundations course. It explores how machine learning can help predict whether a person earns more or less than $50K per year based on U.S. Census income data.

---

## 🎯 Project Overview

In this project, I built and evaluated a machine learning classifier using the K-Nearest Neighbors (KNN) algorithm to predict income brackets (`<=50K` or `>50K`) using demographic and employment data.


## 📌 Objectives and Goals

- Understand the machine learning workflow from data cleaning to model evaluation  
- Explore the impact of class imbalance and feature selection  
- Learn to train, tune, and validate a classification model  
- Gain hands-on experience using scikit-learn and pandas

---

## 🧪 Methodology

1. Data Preprocessing  
   - Cleaned missing values  
   - Encoded categorical features  
   - Scaled features using `StandardScaler`  

2. Modeling
   - Trained a KNN classifier  
   - Used evaluation metrics: Accuracy, Precision, Recall, F1 Score  
   - Investigated model performance issues and class imbalance  

3. Model Tuning 
   - Performed grid search to find the best `k` value  
   - Tested other models (Logistic Regression, Decision Tree) for comparison  

---

## 📊 Results & Key Findings

- **Final Accuracy**: 83%  
- **Precision**: ~0.67  
- **Recall**: ~0.60  
- **F1 Score**: ~0.63  
- **Key Insight**: Model initially struggled due to class imbalance (75% `<=50K`, 25% `>50K`). After tuning and scaling, performance improved significantly.  

---

## 🔧 Tech Stack

**Languages**: Python  
**Libraries**: `pandas`, `scikit-learn`, `matplotlib`, `seaborn`  
**Tools**: Jupyter Notebook, Google Colab, Git/GitHub  
**ML Techniques**: Data preprocessing, KNN, hyperparameter tuning, performance evaluation  

---

## 🤝 Break Through Tech Fellow Experience

As a **Break Through Tech Fellow**, I developed both technical and professional skills:
- Machine learning foundations and Python for AI
- Problem-solving and debugging ML workflows
- Communicating results through visualizations and reports
- Collaborating and receiving feedback from instructors and peers

This project represents a core part of my AI journey — connecting theory to a real-world dataset while improving my modeling and analysis abilities.
