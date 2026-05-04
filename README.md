# 🧠 Obesity Prediction Analysis

## 📌 Project Overview
This project explores the relationship between lifestyle factors and obesity, and builds machine learning models to predict obesity status.

---

## 🎯 Objective
To identify key lifestyle variables associated with obesity and evaluate predictive performance using classification models.

---

## 📊 Dataset Description
The dataset contains lifestyle-related features:

- calorie_intake
- sugar
- fat
- fiber
- water_intake
- exercise_freq
- sleep_hours
- sedentary_hours
- fast_food_freq

Target variable:
- Normal (0)
- Obese (1)

---

## 🔍 Exploratory Data Analysis (EDA)

- 📦 Boxplots: Compare feature distribution between Normal vs Obese
- 📉 T-test: Identify statistically significant differences
- 🔥 Correlation heatmap: Explore relationships between variables

---

## 📉 Dimensionality Reduction

- PCA (Principal Component Analysis)
- Visualize separation between groups in 2D space

---

## 🤖 Machine Learning Models

### 1. Logistic Regression
- Interpretable model
- Outputs probability of obesity

### 2. Random Forest
- Ensemble model
- Captures nonlinear relationships

---

## 📈 Model Evaluation

- Confusion Matrix
- Accuracy Score
- 5-fold Cross Validation

---

## 🔬 Feature Importance

- Logistic Regression coefficients
- Random Forest feature importance

---

## 📊 Clustering Analysis

- KMeans clustering (k=2)
- Hierarchical clustering (clustermap visualization)

---

## 🧠 Key Findings

- Dietary and lifestyle factors show correlation with obesity
- Machine learning models provide reasonable prediction performance
- Certain features contribute more strongly to classification

---

## 🛠 Tools & Libraries

- Python
- pandas
- seaborn
- matplotlib
- scikit-learn

---

## 📁 Project Structure
obesity-project/
│
├── data/
├── notebooks/
│ └── obese_analysis.ipynb
├── README.md


## 🚀 Future Improvements

- Use real clinical datasets
- Add more advanced models (XGBoost, Neural Networks)
- Hyperparameter tuning
- Feature engineering

---

## 👤 Author

- Name: Xiao Juan
