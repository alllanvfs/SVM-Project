# Wine Fraud Detection using SVM

## Project Description
This project applies a Support Vector Machine (SVM) model to detect fraudulent wine quality reports. The dataset contains various chemical properties of wines, and the goal is to classify them as either "Legit" or "Fraud" using machine learning techniques.

## Features and Improvements
- **Exploratory Data Analysis (EDA):**
  - Visualization of numerical feature distributions.
  - Correlation heatmap to understand relationships between variables.
- **Data Preprocessing:**
  - Handling categorical variables via encoding.
  - Standardization of numerical features using `StandardScaler`.
- **Hyperparameter Tuning:**
  - Optimizing the SVM model using `RandomizedSearchCV` for better performance.
- **Model Evaluation:**
  - Classification report with precision, recall, and F1-score.
  - Confusion matrix to visualize prediction performance.
  - ROC curve and AUC score to measure classification effectiveness.
- **Feature Importance Analysis:**
  - Identification of key chemical properties that influence classification.

## Dataset Information
The dataset consists of several physicochemical properties of wines, including:
- **Fixed acidity**
- **Volatile acidity**
- **Citric acid**
- **Residual sugar**
- **Chlorides**
- **Free sulfur dioxide**
- **Total sulfur dioxide**
- **Density**
- **pH**
- **Sulphates**
- **Alcohol**
- **Wine type (Red/White)**
- **Quality (Legit/Fraud)** (Target Variable)

## Results
- **The SVM model successfully classifies fraudulent wines with a high degree of accuracy.**
- **The confusion matrix and classification report provide insights into model performance.**
- **The ROC curve and AUC score validate the robustness of the classification process.**
- **Feature importance analysis helps understand which variables contribute most to fraud detection.**
