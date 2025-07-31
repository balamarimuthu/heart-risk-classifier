# Heart Risk Classifier 🫀

This project uses an XGBoost classifier to predict the risk of heart disease based on patient data. It includes model training, feature importance analysis, and performance evaluation.

-----

## 🔍 Project Overview

  - **Model Used**: XGBoost Classifier
  - **Dataset**: `heart.csv`
  - **Key Files**:
      - `xgboost.ipynb`: Notebook for data exploration and model training.
      - `feature_importance_df.csv`: Script to generate feature importance visuals.
  - **Goal**: Predict whether a person has a high risk of heart disease (binary classification).

-----

## 📊 Performance & Feature Importance

### ✅ ROC AUC Curve

The Receiver Operating Characteristic (ROC) curve evaluates the model’s ability to distinguish between high-risk and low-risk patients. A higher Area Under the Curve (AUC) indicates better performance.

> **AUC Score**: **0.89** (example value)

### 🧠 Feature Importance

Feature importance was calculated to understand which factors contribute most to the model's predictions.

  - **Most Important**: `ST_Slope` was found to be the most influential feature.
  - **Strong Influence**: `ExerciseAngina` and `ChestPainType`.
  - **Moderate Influence**: `Cholesterol`, `Oldpeak`, and `Sex`.

The SHAP summary plot below visualizes the impact of each feature. Red points indicate a high feature value pushing the prediction higher, while blue points indicate a low feature value pushing the prediction lower.

-----

## ⚙️ How to Run

1.  **Clone the repo:**

    ```bash
    git clone https://github.com/yourusername/heart-risk-classifier.git
    cd heart-risk-classifier
    ```

2.  **Install dependencies:**

    ```bash
    pip install -r requirements.txt
    ```

3.  **Run the project:**

      - Open and run the `xgboost.ipynb` notebook for a step-by-step walkthrough.
      - Alternatively, run the Python scripts to train the model and generate plots.

-----

## 📦 Requirements

```
xgboost
pandas
numpy
matplotlib
shap
```

-----

## 📜 License

Licensed under the Apache License 2.0.

-----

## 🧠 Author

Made with ❤️ by Bala Marimuthu
