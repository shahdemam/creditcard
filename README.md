# 💳 Credit Card Fraud Detection

This machine learning project focuses on detecting fraudulent credit card transactions using various classification algorithms. The dataset is highly imbalanced, and multiple preprocessing techniques were applied to enhance model performance.

## 📊 Dataset
- Real credit card transaction data from a European cardholder.
- Features:
  - `V1` to `V28`: Principal Components (PCA-transformed)
  - `Amount`: Transaction amount
  - `Time`: Time in seconds since the first transaction
  - `Class`: Target variable (0 = legitimate, 1 = fraud)

## 🔧 Preprocessing Steps
- **Outlier Detection and Treatment**: Handled outliers in the dataset
- **SMOTE**: Applied Synthetic Minority Oversampling Technique to balance the dataset
- **Feature Scaling** using:
  - `StandardScaler` or `MinMaxScaler`
- Dropped/Handled any missing values (if applicable)
- Splitted the data into training and testing sets

## 🤖 Classification Models Used
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
- Accuracy
- Precision, Recall, F1-Score
- Confusion Matrix
- ROC-AUC Score

## 🛠️ Tools & Libraries
- Python
- Pandas, NumPy
- Scikit-learn
- imbalanced-learn (`SMOTE`)
- XGBoost
- Matplotlib, Seaborn

---

### 📎 Notes
This project handles:
- Highly imbalanced dataset using **SMOTE**
- Scaling for distance-sensitive algorithms (e.g., KNN, SVM)
- **Outlier treatment** for cleaner data and better model training

📁 Check the Jupyter Notebook for complete implementation and visual insights.
