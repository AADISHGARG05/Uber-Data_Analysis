🚕 Uber Data Analysis & Fare Prediction
This project focuses on performing a comprehensive data analysis and building a predictive model for Uber fare prices. Using real-world Uber trip data, we explore factors influencing fare variability and apply machine learning models to predict ride costs accurately.

📊 Project Overview
Ride-sharing services like Uber revolutionize transportation with dynamic pricing strategies. Our study investigates:

Fare variability over time and location

Key features impacting price (e.g., distance, day, time, surge pricing, weather)

Predictive modeling using Regression and Random Forest

📁 Dataset
Source: Kaggle

Format: .csv

Shape: 1155 rows × 7 columns

Attributes: Start Time, End Time, Locations, Distance, Fare, etc.

🔧 Data Preprocessing
Removed duplicates and handled missing values

Feature engineering (added Month, Day, Weekend_Or_Not, Week Day, time-based labels)

Outlier detection and removal

Label encoding and scaling with Standard Scaler

🧠 Models Used
Linear Regression

Random Forest Regressor

Comparison based on:

MAE (Mean Absolute Error)

RMSE (Root Mean Squared Error)

R² Score

📈 Key Insights
Fare is heavily influenced by:

Distance traveled

Time of day

Day of the week

Weather conditions

Surge pricing

Random Forest performed better in most scenarios with higher accuracy.

🛠️ Implementation Highlights
Extracted geocoordinates using MapQuest API

Routes plotted using OpenRouteService

Applied Recursive Feature Elimination (RFE) for feature selection

Fare prediction function created to take input features and return estimated price

📌 Results
Created a reliable fare prediction model

Delivered insights useful for both Uber and its users

Model can be generalized for other ride-sharing platforms

📚 Tools & Libraries
Python (Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn)

Jupyter Notebook

APIs: MapQuest, OpenRouteService
