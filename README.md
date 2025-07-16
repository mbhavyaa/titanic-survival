# titanic-survival


This project predicts the survival of passengers aboard the Titanic using machine learning models. It is based on the famous [Kaggle Titanic dataset](https://www.kaggle.com/c/titanic).

---

## 📌 Overview

The goal is to build a classification model to predict whether a passenger survived based on features like age, gender, class, etc. Several models were trained and evaluated, and the best-performing model was chosen based on accuracy score.

---

## 🧪 Models Used

The following models were implemented and compared:

- **Logistic Regression**
- **Decision Tree Classifier**
- **Random Forest Classifier**
- **XGBoost Classifier**
- **LightGBM Classifier** ✅ *Best Accuracy*

**✅ Best Model:** `LightGBM`, which achieved the highest accuracy score among all tested models.

---

## 📊 Exploratory Data Analysis (EDA) & Preprocessing

Key steps in data preparation:

- **Handled Missing Values:**
  - Mean imputation for numerical columns 
  - Mode imputation for categorical columns 
  - Median imputation where more appropriate 

- **Feature Engineering:**
  - Converted categorical variables using `LabelEncoder` and `pd.get_dummies`
  - Dropped unnecessary columns such as `Name` 

- **Normalization / Scaling:**
  - Applied standard scaling where needed (especially for models like Logistic Regression)

---

## 🧠 Model Evaluation

Models were evaluated using:
- **Accuracy Score**




