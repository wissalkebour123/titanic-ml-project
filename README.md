# 🚢 Titanic Survival Prediction (Machine Learning)

## 📌 Project Overview
This project aims to predict whether a passenger survived the Titanic disaster using Machine Learning techniques.

The project follows a complete ML pipeline:
- Data exploration
- Data cleaning and preprocessing
- Feature engineering
- Model training
- Hyperparameter tuning
- Model evaluation

---

## 📊 Dataset
- Source: Titanic dataset
- Contains passenger information such as age, gender, class, fare, etc.

---

## 🧠 Problem Type
- Binary Classification  
- Target variable: **Survived (0 = No, 1 = Yes)**

---

## ⚙️ Steps Performed

### 1. Data Cleaning
- Handled missing values (Age, Embarked)
- Removed columns with too many missing values (Cabin)

### 2. Feature Engineering
- Converted categorical variables (Sex, Embarked)
- Removed irrelevant columns (Name, Ticket, PassengerId)

### 3. Model Training
- Used **Random Forest Classifier**

### 4. Hyperparameter Tuning
- Used **GridSearchCV**
- Optimized parameters such as:
  - n_estimators
  - max_depth
  - min_samples_split

### 5. Evaluation
- Accuracy: **~85%**
- Confusion Matrix
- Precision, Recall, F1-score

---

## 📈 Results

| Metric | Score |
|------|------|
| Accuracy | ~0.85 |
| F1-score (Survived) | ~0.81 |
| Recall (Survived) | ~0.76 |

👉 The model performs well overall but misses some true survivors (false negatives).

---

## 🛠️ Technologies Used
- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib

---

## 🚀 Future Improvements
- Improve recall for the positive class
- Try advanced models (XGBoost, Gradient Boosting)
- Feature engineering improvements

---

## 💡 Key Learnings
- Data preprocessing is critical
- Model tuning improves performance and stability
- Evaluation metrics beyond accuracy are important

---

## 👨‍💻 Author
**Wissal Kebour**

GitHub: https://github.com/issalkebour123
