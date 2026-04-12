# AAI590 Capstone Project: Customer Churn Prediction

**Author:** D. Keith Holder  
**Course:** AAI 590 – Capstone  

---

## 📌 Overview
This project develops a complete machine learning pipeline to predict customer churn in a bundled streaming services environment. The model integrates customer behavior, subscription details, and billing data to identify users at risk of canceling their service.

The goal is to evaluate whether advanced machine learning techniques improve churn prediction compared to simpler baseline models.

---

## ⚙️ Models Implemented
The following models were developed and evaluated:

- Logistic Regression (Best Performing Model)
- Decision Tree
- Random Forest
- AdaBoost
- Gradient Boosting
- Multi-Layer Perceptron (MLP Neural Network)
- Stacked Ensemble Model

---

## 📊 Key Results
- **Logistic Regression achieved the best performance**
  - Accuracy: ~80.9%
  - ROC-AUC: ~0.85
- Ensemble and deep learning models performed competitively but did not outperform Logistic Regression
- The stacked model underperformed, indicating limited model diversity

👉 **Key Insight:** Increasing model complexity did not improve performance for this dataset.

---

## 📁 Notebook Contents
The main notebook includes:

- Data ingestion and cleaning
- Feature engineering (Customer 360 view)
- Data preprocessing and encoding
- Model training and evaluation
- Model comparison and analysis
- Visualization of training performance
- Final model selection

---

## 🚀 How to Run
1. Open the notebook in Google Colab or Jupyter
2. Run all cells from top to bottom:
   - `Runtime → Run all`
3. Review outputs, visualizations, and model comparisons

---
