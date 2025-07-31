# 🧠 Heart Disease Prediction using XGBoost

This project uses the **XGBoost machine learning algorithm** to predict the presence of heart disease based on patient data.

## 📁 Project Structure

- `xgboost.py`: Trains the XGBoost model on the dataset.
- `feature_importance_df.csv`: Generates a plot showing the importance of each feature.
- `heart data.csv`: The dataset used for training and testing.


## 📊 Feature Importance (Gain Based)

The model ranked features by how much they improved decision trees:

- **ST_Slope**: Most important feature (~50%)
- **ExerciseAngina**, **ChestPainType**: Strong influence
- **Cholesterol**, **Oldpeak**, **Sex**: Moderate influence
- Other features (Age, MaxHR, FastingBS, RestingBP, etc.) had lower importance

## 🛠️ Requirements

- Python 3.x  
- Libraries: `xgboost`, `pandas`, `matplotlib`

Install dependencies with:

```bash
pip install xgboost pandas matplotlib
