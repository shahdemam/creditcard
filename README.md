# 💳 Credit Card Customer Classification

This machine learning project focuses on classifying credit card customers based on their behavior and financial features. The aim is to identify customer types or potential churn using classification algorithms.

## 📊 Dataset
The dataset includes features such as:
- Credit Limit
- Balance
- Purchases
- Payments
- Tenure
- And other behavioral and demographic variables

## 🔧 Preprocessing
- Handled missing/null values
- Applied **Feature Scaling** using:
  - `StandardScaler`
  - `MinMaxScaler`
- Encoded categorical variables (if needed)
- Performed train-test split

## 🤖 Models Applied
- Logistic Regression
- Naive Bayes
- K-Nearest Neighbors (KNN)
- Decision Tree
- Support Vector Classifier (SVC)
- AdaBoost Classifier
- XGBoost Classifier (`xgb.XGBClassifier`)
- **GridSearchCV** for hyperparameter tuning

📝 *Note: Random Forest was not used in this project.*

## 📈 Evaluation Metrics
- Accuracy Score
- Confusion Matrix
- Classification Report (Precision, Recall, F1 Score)
- (Optional) ROC Curve / AUC

## 🛠️ Tech Stack
- Python
- Pandas, NumPy
- Scikit-learn
- XGBoost
- Matplotlib, Seaborn for visualization

---

### 📎 Notes
This project compares different classification models and highlights the importance of **data preprocessing** and **scaling** for performance. The use of multiple algorithms with `GridSearchCV` helped in identifying the best-performing model.

👉 Check the notebook for full implementation and visual insights.
