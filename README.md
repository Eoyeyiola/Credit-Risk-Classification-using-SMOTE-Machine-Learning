# Credit Risk Classification: An Analysis using SMOTE and Machine Learning

## Introduction
Many lending institutions struggle to accurately classify loan statuses, especially when working with imbalanced datasets. Rare cases such as "Charged Off" or "Late" are often underrepresented, leading to biased models that mostly predict the majority class (e.g., "Current"). This project aims to address this challenge using a data-driven approach.

## Dataset
- **Source:** [Lending Club Loan Data (2007–2015)](https://www.kaggle.com/datasets/adarshsng/lending-club-loan-data-csv)
- **Size:** 890,000+ observations, 75 variables

## Objective
To build a machine learning model that accurately predicts loan status across multiple categories by handling class imbalance and evaluating performance across several metrics.

## Tools & Technologies
- Python (Pandas, NumPy, Scikit-learn, Imbalanced-learn)
- Power BI (for visualization)

## Approach
### 1. Data Cleaning & Preprocessing
- Removed columns with over 50% missing values
- Dropped or imputed missing values for other features
- Encoded categorical variables

### 2. Addressing Class Imbalance
- Used **SMOTE (Synthetic Minority Oversampling Technique)** to oversample minority classes
- Compared model performance before and after SMOTE

### 3. Model Building
- Trained multiple classifiers: Logistic Regression, Random Forest, and XGBoost
- Evaluated using Accuracy, Precision, Recall, F1-Score, and Confusion Matrix

### 4. Visualization
- Created interactive dashboards in Power BI to display:
  - Class distribution before and after SMOTE
  - Confusion matrices
  - Feature importance
  - Model performance comparison

## Key Findings
1. **Severe class imbalance** resulted in poor recall for minority classes without SMOTE.
2. **SMOTE significantly improved** model recall and F1-scores for "Charged Off" and "Late" statuses.
3. **Accuracy is not sufficient** to evaluate models on imbalanced data — recall, precision, and confusion matrices revealed the full picture.
4. **Some misclassifications remain**, suggesting the need for further tuning and possibly more advanced techniques.

## Visual Results
Power BI dashboards include:
- SMOTE Comparison Charts
- Confusion Matrices
- Model Accuracy Tables
- Feature Importance Visualizations

➡️ [Explore Live Dashboard] - (https://www.novypro.com/create_project/credit-risk-classification-using-smote--machine-learning) 

## Conclusion
This project successfully demonstrates how to handle class imbalance using SMOTE and how different machine learning models perform under such conditions. It highlights the need for ethical, balanced, and thoughtful modeling practices in financial risk classification.

## Future Work
- Fine-tuning model hyperparameters
- Experimenting with ensemble methods or deep learning
- Exploring cost-sensitive learning for high-risk misclassifications

## Medium Article
📝 [Read Full Story on Medium](https://medium.com/@Emaleecious/credit-risk-classification-an-analysis-using-smote-and-machine-learning-6e50cc3776cf)

## Connect
📬 Feel free to connect or share your thoughts on [LinkedIn](https://www.linkedin.com/in/eoyeyiola/)!

---

**Tags:** #DataScience #MachineLearning #Python #CreditRisk #PowerBI #SMOTE #PortfolioProject

