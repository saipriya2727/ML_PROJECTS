# 📉1.Machine Learning-Based Customer Churn Prediction for Consulting Firms
 # 👩‍💻Author

Reddy Sai Priya
B.Tech CSE (AI & ML Specialization) | Aspiring Data Analyst / AI-ML Engineer

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


## 🌍2.Location-Based Analysis of Restaurants
# 👩‍💻 Author
    
 Reddy Sai Priya
 B.Tech CSE (AI & ML Specialization) | Aspiring Data Analyst / AI-ML Engineer

# 📌 Project Overview
This project performs Location-Based Data Analysis on restaurant data to identify:
📍 Geographical distribution of restaurants
🏙️ Top cities with highest restaurant density
⭐ Cities and localities with highest average ratings
💰 Price trends across different cities
📊 Voting and engagement patterns
The analysis combines Data Analytics + Geospatial Visualization to extract actionable business insights.

# 🎯 Objectives
Analyze restaurant distribution using latitude and longitude
Identify top-performing cities by ratings
Discover high-rated localities
Visualize restaurant density geographically
Compare price range and popularity across cities

# 🛠️ Tech Stack
Python
Pandas (Data Analysis)
Matplotlib (Visualization)
Seaborn (Statistical Visualization)
Folium (Interactive Maps)

# 📂 Dataset
File Used: Dataset.csv
Important Columns Used:
City
Locality
Restaurant Name
Latitude
Longitude
Aggregate Rating
Price Range
Votes

# ⚙️ Analysis Workflow
1️⃣ Data Cleaning
Removed rows with missing latitude & longitude
Ensured only valid geographic records were analyzed
2️⃣ Top Cities Identification
Used value_counts()
Identified top 10 cities with highest number of restaurants
3️⃣ 🌍 Interactive Restaurant Map
An interactive global map was created using Folium, plotting 500 sampled restaurant locations for clarity.
✔ Each marker represents a restaurant
✔ Popup shows restaurant name
✔ Map saved as: restaurant_locations_map.html
4️⃣ 📊 City-Level Statistical Analysis
Grouped data by City to calculate:
Average Rating
Average Price Range
Average Votes
✔ Identified Top 10 Cities by Average Rating
5️⃣ 📍 Locality-Level Analysis
Grouped by:
City + Locality
Calculated:
Average Rating
Average Price
Average Votes
Restaurant Count
✔ Identified Top 10 Localities by Rating
6️⃣ 📈 Geographical Distribution Visualization
Scatter plot of restaurants based on Latitude & Longitude:
✔ Shows density patterns
✔ Highlights urban clustering
7️⃣ 🏙️ Top Cities by Restaurant Count
Bar chart visualization of top 10 cities:
✔ Identifies major food hubs
✔ Useful for market expansion strategy

# 📊 Key Insights
Major metropolitan cities have higher restaurant concentration
High-rating cities do not always have highest restaurant counts
Some localities show premium pricing trends
Restaurant clustering indicates urban demand zones

# 💼 Business Applications
✔ Market Expansion Planning
✔ Restaurant Chain Growth Strategy
✔ Pricing Optimization
✔ Location Intelligence for Food Delivery Platforms
✔ Investment Decision Support

# 📦 Installation
pip install pandas matplotlib seaborn folium

# ▶️ How to Run
Place Dataset.csv in project folder
Run the Python script or Jupyter Notebook
Open restaurant_locations_map.html to view interactive map

# 🧠 Skills Demonstrated
Data Cleaning & Preprocessing
Exploratory Data Analysis (EDA)
Groupby & Aggregation
Geospatial Data Visualization
Statistical Comparison
Business Insight Extraction

# 🚀 Future Enhancements
Heatmap visualization for restaurant density
Clustering using K-Means
Geo-spatial clustering using DBSCAN
Interactive dashboard using Streamlit
Predictive model for location-based success

# 📬 Contact
📧 reddysaipriya2727@gmail.com

## ⭐3. Predict Restaurant Ratings using Machine Learning
# 👩‍💻 Author

Reddy Sai Priya
B.Tech CSE (AI & ML Specialization)Aspiring AI/ML Engineer | Data Analyst

# 📌 Project Overview
This project builds a Regression Machine Learning model to predict restaurant ratings based on features such as:
Cuisine type
City
Price range
Votes
Delivery options
Table booking availability
The objective is to estimate the Aggregate Rating of a restaurant using structured data and identify key factors influencing customer satisfaction.

# 🎯 Problem Statement
Predict the Aggregate Rating (continuous variable) of restaurants using supervised machine learning techniques.
This is a Regression Problem.

# 🛠️ Tech Stack
Python
Pandas
NumPy
Matplotlib
Seaborn
Scikit-learn

# 📂 Dataset
File Used: Dataset.csv
Important Columns Used:
Restaurant Name
City
Cuisines
Price Range
Votes
Has Table Booking
Has Online Delivery
Aggregate Rating (Target Variable)

# ⚙️ Machine Learning Workflow
1️⃣ Data Preprocessing
✔ Removed irrelevant columns:
Restaurant ID
Address
Locality Verbose
Switch to Order Menu
✔ Handled Missing Values
✔ Filled missing cuisine values using mode
✔ Dropped remaining null values
2️⃣ Encoding Categorical Variables
Used Label Encoding
Converted object-type columns into numeric format
Stored encoders for future predictions
3️⃣ Train-Test Split
80% Training Data
20% Testing Data
Random state fixed for reproducibility
4️⃣ Model Training
Model Used: Random Forest Regressor
n_estimators = 100
random_state = 42
Random Forest was chosen because:
Handles non-linear relationships
Reduces overfitting
Provides feature importance

# 📊 Model Evaluation
Evaluation Metrics Used:
Mean Squared Error (MSE)
R-squared (R² Score)
✔ Lower MSE indicates better prediction accuracy
✔ R² close to 1 indicates strong model performance

# 📈 Feature Importance Analysis
The model identifies which features most influence restaurant ratings.
Insights:
Votes often strongly impact rating
Price range influences customer perception
Location-based factors affect performance

# 📊 Skills Demonstrated
✔ Data Cleaning & Preprocessing
✔ Feature Engineering
✔ Categorical Encoding
✔ Regression Modeling
✔ Random Forest Algorithm
✔ Model Evaluation Metrics
✔ Data Visualization

# 💼 Business Applications
Restaurant performance prediction
Investment decision support
Market analysis
Food delivery platform optimization
Rating prediction for new restaurants

#📦 Installation
pip install pandas numpy matplotlib seaborn scikit-learn
▶️ How to Run
Place Dataset.csv inside the project folder
Run the Python script or Jupyter Notebook
View MSE and R² score
Analyze feature importance plot

# 🚀 Future Improvements
Hyperparameter tuning using GridSearchCV
Try XGBoost / Gradient Boosting
Cross-validation for better generalization
Model deployment using Streamlit
Build a restaurant rating prediction web app

# 📬 Contact
📧 reddysaipriya2727@gmail.com

# 🍽️4.Restaurant Recommendation System using TF-IDF & Cosine Similarity
# 👩‍💻 Author

Reddy Sai Priya
B.Tech CSE (AI & ML Specialization)Aspiring AI/ML Engineer | NLP Enthusiast | Data Analyst

# 📌 Project Overview
This project builds a Content-Based Restaurant Recommendation System using Natural Language Processing (NLP).
The system recommends restaurants based on cuisine similarity, using:
TF-IDF Vectorization
Cosine Similarity
If a user selects a restaurant, the system suggests similar restaurants based on cuisine type.

# 🎯 Problem Statement
Given a restaurant name, recommend similar restaurants based on cuisine similarity.
This is a Content-Based Filtering Recommendation System.

# 🛠️ Tech Stack
Python
Pandas
Matplotlib
Seaborn
Scikit-learn
TfidfVectorizer
Cosine Similarity

# 📂 Dataset
File Used: Dataset.csv
Important Columns:
Restaurant Name
Cuisines
City

# ⚙️ Project Workflow
1️⃣ Data Preprocessing
✔ Filled missing cuisine values
✔ Converted cuisine text to lowercase
✔ Cleaned text for consistent comparison
2️⃣ Text Vectorization (TF-IDF)
Used:
TfidfVectorizer(stop_words='english')
TF-IDF converts cuisine text into numerical vectors representing importance of each term.
Example:
"North Indian, Chinese"
"Chinese, Thai"
The model detects similarity based on shared cuisine words.
3️⃣ Cosine Similarity Calculation
Computed similarity between all restaurants:
cosine_similarity(tfidf_matrix, tfidf_matrix)
✔ Measures similarity between cuisine vectors
✔ Value ranges from 0 to 1
✔ Higher value → More similar
4️⃣ Recommendation Function
def recommend_restaurants(name, top_n=5)
✔ Takes restaurant name as input
✔ Finds most similar restaurants
✔ Returns top N recommendations
📊 Cuisine Analysis
Top 15 most common cuisines were visualized.
Insights:
Identified most popular cuisines
Useful for market demand analysis
Helps understand customer preferences

# 🧠 How Recommendation Works
Convert cuisine text → TF-IDF vectors
Compute cosine similarity matrix
Find similarity scores for selected restaurant
Sort and return top similar restaurants
This is:
✔ Content-Based Filtering
✔ NLP-Based Recommendation
✔ No collaborative user data required

# 📈 Skills Demonstrated
✔ Natural Language Processing (NLP)
✔ TF-IDF Vectorization
✔ Cosine Similarity
✔ Content-Based Recommendation Systems
✔ Text Data Cleaning
✔ Exploratory Data Analysis
✔ Data Visualization

# 💼 Business Applications
Food delivery platforms (like Swiggy, Zomato)
Restaurant discovery apps
Personalized dining recommendations
Cuisine trend analysis
Location-based recommendation systems

# 📦 Installation
pip install pandas matplotlib seaborn scikit-learn
# ▶️ How to Run
Place Dataset.csv in project folder
Run the script or notebook
Call:
recommend_restaurants("Restaurant Name")
View top recommended restaurants

# 🚀 Future Improvements
Add location filtering
Include rating-based ranking
Hybrid recommendation system
Deploy using Streamlit
Add user preference input

# 📬 Contact
📧 reddysaipriya2727@gmail.com


