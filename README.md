# Churn_Prediction

**Project Overview:**
Customer churn can significantly affect a telecom company's revenue and market share. This project leverages a comprehensive dataset and explores various machine learning models to predict which customers are likely to churn, enabling targeted retention measures.

**Key Features:**

**Data Preprocessing:**
Handled missing values and dropped irrelevant columns.
Performed feature selection by analyzing correlations and removing highly correlated features.
Addressed class imbalance using SMOTE (Synthetic Minority Over-sampling Technique).

**Exploratory Data Analysis (EDA):**
Identified key factors contributing to customer churn such as account balance, outgoing activity, and service usage patterns.
Visualized insights with graphs showing the relationship between churn and factors like outgoing calls, SMS, and GPRS usage.

**Predictive Modeling:**
Trained 9 machine learning models, including Decision Trees, Random Forest, and XGBoost.
Achieved the highest F1 score and accuracy using the XGBoost model.
Performed hyperparameter tuning on XGBoost to optimize model performance.

**Model Evaluation:**
Evaluated models based on Accuracy, Precision, Recall, and F1 Score.
The final XGBoost model achieved an accuracy of 80.4% on the test dataset.

**Feature Importance:**
Key features contributing to churn prediction include customer lifetime, intake, and outgoing activity.

**Tools & Libraries:**
Python: Core programming language.
Pandas & NumPy: For data manipulation.
Matplotlib & Seaborn: For data visualization.
Scikit-learn & XGBoost: For building and evaluating machine learning models.
Imbalanced-learn (SMOTE): For handling class imbalance.

**Results:**
Best Model: XGBoost Classifier.
Test Accuracy: 80.4%
Key Features: Customer lifetime, intake, outgoing activity.

**Future Scope:**
Improving model precision for the churners class.
Exploring deep neural networks as a potential approach to enhance prediction accuracy, especially with larger datasets.
