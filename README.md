

# Accident Outcome Prediction using Machine Learning

Accidents remain a critical global issue, demanding advanced techniques for real-time decision-making and efficient resource allocation. This project applies **machine learning algorithms** to predict two crucial outcomes: **Injury Type** and **Patient Status** based on accident-related features.

## 📌 Project Overview

* **Goal:** Improve accident response strategies by predicting injury type and patient status.
* **Approach:** Six machine learning models were trained and optimized on a robust dataset with extensive preprocessing.
* **Key Tasks:**

  1. Predict **Injury Type** (classification task)
  2. Predict **Patient Status** ("Alive & stable", "Alive & unstable", "Dead")

## 🔬 Methodology

1. **Data Preprocessing**

   * Handling missing values
   * Outlier detection
   * Feature engineering
   * Data scaling

2. **Models Used**

   * Logistic Regression
   * Decision Tree
   * Random Forest
   * XGBoost
   * Support Vector Machine (SVM)
   * Artificial Neural Network (ANN)

3. **Evaluation Metrics**

   * Accuracy
   * Precision
   * Recall
   * F1 Score

4. **Hyperparameter Tuning**

   * Grid Search and cross-validation to optimize performance

## 📊 Results

### **Injury Type Prediction**

* **Logistic Regression:** *76.57% accuracy* (highest performance)
* **SVM:** *76.56% accuracy* (very competitive)
* **XGBoost:** *76.51% accuracy*
* **Random Forest:** *72.70% accuracy* (robust but slightly less suited under current settings)

### **Patient Status Prediction**

* **Decision Tree:** *69.61% accuracy, 68.89% F1 score* (best overall performance)
* **SVM:** *69.60% accuracy*
* **ANN:** *69.58% accuracy*
* **XGBoost:** *69.47% accuracy*
* **Logistic Regression:** *63.63% accuracy* (struggled with multi-class complexity)

**Key Insight:** Including *Injury Type* as a feature significantly improved patient status prediction.


