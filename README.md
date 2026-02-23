# 📉Machine Learning-Based Customer Churn Prediction for Consulting Firms
 # 👩‍💻Author

Reddy Sai Priya
B.Tech CSE (AI & ML Specialization) | Aspiring AI/ML Engineer

# 📌 Project Overview
Customer churn is a critical challenge for consulting firms, directly impacting revenue and long-term client relationships.
This project builds a Machine Learning classification model to predict whether a customer is likely to churn based on engagement metrics, health scores, and satisfaction indicators.
The solution helps consulting firms:
✅ Identify high-risk customers
✅ Improve customer retention strategies
✅ Reduce revenue loss
✅ Enable proactive decision-making

# 🎯 Problem Statement
Predict whether a customer will churn (1) or not churn (0) using behavioral and performance metrics.
The churn target is created using business logic:
Lifecycle Stage = Churned or Inactive
OR Health Score < 4
OR Engagement Score < 30

# 🛠️ Tech Stack
Programming Language: Python
Libraries:
Pandas
NumPy
Scikit-learn
Matplotlib

# 📂 Dataset
File Used: PrimePath_Contacts_15000.csv
Records: 15,000 customer entries

# 🔑 Features Used for Modeling
EngagementScore
HealthScore
NPSLastScore
CSATScore
IsActive
DoNotContact

# ⚙️ Machine Learning Workflow
1️⃣ Data Loading
    Imported dataset using Pandas
2️⃣ Target Creation (Churn Column)
    Created a binary classification target using business conditions.
3️⃣ Feature Selection
    Selected only safe and relevant numerical features.
4️⃣ Data Preprocessing
    Handled missing values
    Converted boolean values to integers
5️⃣ Train-Test Split
    80% Training Data
    20% Testing Data
    Stratified split for balanced classes
6️⃣ Model Training
    Model Used: Random Forest Classifier
    n_estimators = 200
    max_depth = 10
    random_state = 42
7️⃣ Model Evaluation
    Accuracy Score
    Classification Report (Precision, Recall, F1-score)
  Confusion Matrix

# 📊 Feature Importance Visualization
    The model identifies the most influential features contributing to churn prediction.
    This helps businesses understand:
    Which factors impact churn the most
    Where to focus customer retention efforts

# 📉 Confusion Matrix
    The confusion matrix visualizes:
    True Positives
    True Negatives
    False Positives
    False Negatives
This helps evaluate prediction reliability and classification performance.

# 📈 Model Performance
   The model outputs:
     Overall Accuracy,Precision,Recall,F1-Score
Random Forest performs well for structured customer data and handles feature importance effectively.

# 🚀 Business Impact
✔ Early identification of at-risk customers
✔ Improved customer retention strategy
✔ Data-driven consulting decisions
✔ Scalable ML solution for CRM systems

# 📦 Installation
pip install pandas numpy scikit-learn matplotlib
▶️ How to Run:
Place PrimePath_Contacts_15000.csv in the project directory
Run the Python script or Jupyter Notebook
View accuracy, classification report, feature importance, and confusion matrix

# 🧠 Key Concepts Demonstrated
Supervised Machine Learning
Binary Classification
Random Forest Algorithm
Feature Importance Analysis
Model Evaluation Metrics
Business Logic-Based Target Engineering

# 🔮 Future Improvements
Hyperparameter tuning using GridSearchCV
SMOTE for class imbalance handling
Model deployment using Flask or Streamlit
Integration with CRM dashboards
Real-time churn prediction API

# 📬 Contact
📧 reddysaipriya2727@gmail.com
## 🌟 “Predicting Customer Behavior with Data-Driven Intelligence.”
