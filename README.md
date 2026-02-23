**Machine Learning Classification Projects (KNN & Decision Tree)**

This repository contains two supervised machine learning classification projects:

**K-Nearest Neighbors (KNN) – Breast Cancer Prediction**

**Decision Tree Classifier – Loan Approval Prediction**

Each project includes preprocessing, model training, evaluation, visualization, and performance analysis.

**Scenario 1 – KNN Classification**
Breast Cancer Diagnosis Prediction

**Problem Statement**

Predict whether a tumor is Benign or Malignant based on medical measurements.

**Dataset**

Name: Breast Cancer Dataset

Source: Kaggle

Target Variable: Diagnosis (Benign / Malignant)

**Input Features:**

Radius

Texture

Perimeter

Area

Smoothness

**Project Workflow**

1️.Data Preprocessing

Data inspection and summary statistics

Checked for missing values

Encoded target labels (Benign = 0, Malignant = 1)

2️.Feature Scaling (Important for KNN)

Since KNN is distance-based, feature scaling was applied using:

StandardScaler / MinMaxScaler

3️.Model Training

Split dataset into training and testing sets

Trained K-Nearest Neighbors (KNN) classifier

Experimented with multiple values of K

4️.Model Evaluation

Performance measured using:

Accuracy

Precision

Recall

F1 Score

Confusion Matrix

5️.Model Analysis

Identified misclassified cases

Analyzed sensitivity of model to different K values

Compared performance across various K values

**Visualizations**

Confusion Matrix

Accuracy vs K Plot

Decision Boundary (using two selected features)

**Scenario 2 – Decision Tree Classifier**
Loan Approval Prediction

**Problem Statement**

Predict whether a loan application should be Approved or Rejected based on applicant details.

**Dataset**

Name: Loan Prediction Dataset

Source: Kaggle

Target Variable: Loan Status (Approved / Rejected)

**Input Features:**

Applicant Income

Loan Amount

Credit History

Education

Property Area

**Project Workflow**

1️.Data Preprocessing

Handled missing values

Encoded categorical variables (Label Encoding / One-Hot Encoding)

Data cleaning and formatting

2️.Model Training

Split dataset into training and testing sets

Trained Decision Tree Classifier

Experimented with:

Tree depth

Pruning techniques

Criterion (Gini / Entropy)

3️.Model Evaluation

Evaluated using:

Accuracy

Precision

Recall

F1 Score

Confusion Matrix

4️.Model Analysis

Analyzed feature importance

Compared shallow vs deep trees

Detected overfitting behavior

Studied bias-variance tradeoff

**Visualizations**

Confusion Matrix

Tree Structure Plot

Feature Importance Chart

**Conclusion**

This repository demonstrates:

KNN for medical diagnosis classification

Decision Trees for financial decision-making prediction

Both projects highlight practical implementation of supervised learning algorithms with detailed evaluation and visualization.
