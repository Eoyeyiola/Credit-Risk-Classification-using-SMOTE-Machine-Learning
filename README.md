Credit Risk Classification using SMOTE & Machine Learning
This project explores the classification of loan statuses using machine learning models on the Lending Club dataset. A key challenge addressed is the severe class imbalance, which was tackled using SMOTE (Synthetic Minority Oversampling Technique).

Problem Statement
Lending institutions often struggle to identify risky loans due to imbalanced datasets—where "Charged Off" or "Late" statuses are underrepresented. This leads to models biased toward the "Current" class, creating blind spots in risk prediction.

Dataset
Source: Kaggle - Lending Club Loan Data- https://www.kaggle.com/datasets/adarshsng/lending-club-loan-data-csv

Size: 890,000+ rows | 75 columns

Period: 2007–2015

Tools & Techniques
Python (Pandas, Scikit-learn, Matplotlib, Seaborn)

Power BI for Visualization

SMOTE for oversampling minority classes

Logistic Regression, Random Forest, and other ML classifiers

Evaluation metrics: Accuracy, Precision, Recall, F1-score, Confusion Matrix

Approach
Data Cleaning: Removed columns with >50% missing values. Handled NaNs and infinite values.

Feature Engineering: Selected relevant features, encoded categorical variables.

SMOTE Resampling: Balanced the target variable to improve minority class prediction.

Model Building: Trained and tested various classifiers.

Evaluation: Used confusion matrices and classification reports to compare performance.

Visualization: Created performance dashboards in Power BI.

Key Insights
Without SMOTE, the models heavily favored the "Current" class.

SMOTE significantly improved recall for underrepresented classes like "Charged Off."

Despite improvements, some minority classes still had low scores—highlighting the complexity of real-world credit risk classification.

Visuals
Power BI Dashboard & Confusion Matrix Samples:

(https://www.novypro.com/create_project/credit-risk-classification-using-smote--machine-learning)

Links
Medium Article- https://medium.com/@Emaleecious/credit-risk-classification-an-analysis-using-smote-and-machine-learning-6e50cc3776cf

Notebook- 

Let's Connect!
I'd love feedback from data scientists and professionals in the finance and risk analytics space. Feel free to open issues or share insights.

