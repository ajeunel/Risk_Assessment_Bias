
# 📊 VI-SPDAT Score Prediction Capstone

This project explores the use of supervised machine learning models to predict VI-SPDAT assessment scores based on wellness and demographic data, with a focus on fairness and interpretability.

---

## 📁 Files

- `Organized_Feature_Engineering_Capstone.ipynb` — Main notebook containing all steps from preprocessing to model evaluation and fairness auditing.
- `Clean_data_for_model.csv` — Pre-cleaned dataset used in modeling (not included here, upload to Colab).

---

## 📌 Project Overview

This capstone project investigates:
- How accurately VI-SPDAT scores can be predicted using wellness subscores and demographic data.
- Whether race and gender impact predictions when controlling for need.
- What differences in predictions reveal about fairness and potential bias.

---

## 🧱 Notebook Structure

The notebook is organized by the following sections:

### 🧹 Data Preprocessing & Cleaning
- Removes irrelevant columns
- Handles missing data
- Creates a binary high-risk label

### 🧪 Feature Engineering
- One-hot encoding of race, gender, and age group
- Feature scaling with StandardScaler

### 📈 Polynomial Regression
- Uses PolynomialFeatures to model non-linear relationships
- Evaluates model using RMSE, MAE, and R²

### 🔍 Logistic Regression
- Predicts binary high-risk outcome
- Includes cross-validation and regularization



### ✅ Model Evaluation & Interpretation
- Accuracy, ROC AUC, F1-score, precision/recall
- Confusion matrix

### ⚖️ Fairness & Bias Testing
- Simulates predictions across demographic groups
- Audits fairness using randomized wellness profiles

### 🧠 Variable Importance & Interpretability
- Logistic regression coefficients reveal feature influence

---

## 🚀 How to Use

1. Upload `Clean_data_for_model.csv` to Colab.
2. Run all cells in the notebook.
3. Modify and test additional models as needed.
4. Use the final visualizations and outputs in your presentation.

---

## 💬 Credits

Created as part of a master's capstone project on ethical machine learning for human services assessment tools.

