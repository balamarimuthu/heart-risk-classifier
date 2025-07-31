# Heart Risk Classifier 🫀

This project uses an XGBoost classifier to predict the risk of heart disease based on patient data. It includes model training, feature importance analysis, and performance evaluation using SHAP and ROC AUC.

---

## 🔍 Project Overview

- **Model Used**: XGBoost Classifier
- **Dataset**: `heart data.csv`
- **Key Features**: Age, cholesterol, blood pressure, etc.
- **Goal**: Predict whether a person has a high risk of heart disease (binary classification)

---

## 📊 Performance

### ✅ ROC AUC Curve

The Receiver Operating Characteristic (ROC) curve evaluates the model’s ability to separate the two classes.  
Higher AUC indicates better classification performance.

> *AUC Score*: **0.89** (example — replace with actual if needed)

![AUC Curve](./auc.png)

---

### 🧠 SHAP Feature Importance

SHAP (SHapley Additive exPlanations) values were used to interpret the impact of each feature on model predictions.

- Red = High Feature Value
- Blue = Low Feature Value
- X-axis = SHAP contribution to the prediction

![SHAP Summary](./shap.png)

---

## ⚙️ How to Run

1. Clone the repo:
   ```bash
   git clone https://github.com/yourusername/heart-risk-classifier.git
   cd heart-risk-classifier
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Run the notebook:
   Open `xgboost.ipynb` in Jupyter or VSCode.

---

## 📦 Requirements

```
xgboost
pandas
numpy
matplotlib
shap
```

---

## 📜 License

Licensed under the Apache License 2.0.

---

## 🧠 Author

Made with ❤️ by Bala Marimuthu
