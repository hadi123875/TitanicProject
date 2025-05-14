# 🚢 Titanic Survival Prediction

This project uses machine learning (Random Forest and Logistic Regression) to predict survival of passengers aboard the Titanic, based on the [Kaggle Titanic dataset](https://www.kaggle.com/c/titanic).

---

## 🧠 Model Info

The project uses:

- Data cleaning (handling missing values)
- Feature encoding (OneHotEncoder for categorical features)
- Preprocessing with `ColumnTransformer`
- A full pipeline wrapped with `GridSearchCV` for hyperparameter tuning

---

## 📁 Project Structure

titanic-ml-project/
├── data/
│ └── train.csv
├── models/
│ └── best_model.joblib # Saved trained model
├── README.md # Project description
└── .gitignore

## 📊 Model Performance

| Metric    | Value |
| --------- | ----- |
| Accuracy  | 78.2% |
| Precision | 75.3% |
| Recall    | 70.3% |

Model: `RandomForestClassifier` after hyperparameter tuning.
