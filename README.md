# Task 4: Logistic Regression Classifier

## 📌 Objective
To build a binary classification model using **Logistic Regression** to predict whether a tumor is **Malignant** or **Benign** using the Breast Cancer Wisconsin dataset.

---

## 📂 Dataset Used
- **Name:** Breast Cancer Wisconsin (Diagnostic)
- **Source:** [Kaggle Dataset](https://www.kaggle.com/datasets/uciml/breast-cancer-wisconsin-data)
- **Features:** Mean values of cell nuclei properties
- **Target Variable:** 
  - M (Malignant) → 1
  - B (Benign) → 0

---

## 🛠️ Steps Performed
1. Imported the dataset using pandas.
2. Cleaned the data (removed unnecessary columns, encoded labels).
3. Split the data into training and testing sets.
4. Standardized the feature values.
5. Trained a Logistic Regression model.
6. Evaluated the model using:
   - Confusion Matrix
   - Precision, Recall, F1 Score
   - ROC-AUC Score
7. Plotted the ROC Curve.
8. Explained the Sigmoid function used in Logistic Regression.

---

## 📈 Model Evaluation

- **Confusion Matrix:** Shows correct and incorrect classifications.
- **Classification Report:** Provides Precision, Recall, and F1-Score.
- **ROC-AUC Score:** Evaluates model performance in classification tasks.
- **ROC Curve:** Visualizes the trade-off between sensitivity and specificity.

---

## 🧠 Sigmoid Function

The Logistic Regression algorithm uses the **sigmoid function** to map predicted values between 0 and 1:

