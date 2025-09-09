# taxi_ride_fare_prediction-

📌 **Project Overview**

This project focuses on predicting Uber ride fares using advanced machine learning techniques. By analyzing trip-related features such as pickup and drop-off coordinates, datetime, passenger count, and derived trip distance, the objective is to develop a robust model capable of delivering accurate fare predictions.

The final model, a tuned XGBoost Regressor, achieved strong performance with high accuracy and generalization capability.

🎯 **Key Objectives**

1.Perform extensive data preprocessing to ensure data quality.

2.Conduct exploratory data analysis (EDA) to identify trends and patterns.

3.Implement feature engineering for improved predictive power.

4.Train and evaluate multiple machine learning models.

5.Select and fine-tune the best-performing model.

📊 **Dataset Features**

1.Pickup Datetime – Used to derive time-based features (hour, day, month, day of week).

2.Pickup & Drop-off Coordinates – Geospatial data for distance calculation.

3.Passenger Count – Number of passengers per ride.

4.Fare Amount – Target variable for prediction.

🛠 **Technology Stack**

1.Programming Language: Python

2.Core Libraries: Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, XGBoost

3.Development Environment: Jupyter Notebook, Google Colab

🔍 **Methodology**
1. Data Preprocessing

Removed missing values, duplicates, and inconsistent records.

Filtered out invalid latitude/longitude coordinates.

Excluded negative or zero fare values.

2. Feature Engineering

Trip Distance: Computed using the Haversine formula.

Datetime Features: Extracted year, month, day, weekday, and hour.

Passenger Information: Incorporated passenger count as a predictive feature.

3. Model Development

Models evaluated: Linear Regression, Decision Tree, Random Forest, XGBoost.

Hyperparameter tuning performed using RandomizedSearchCV.

XGBoost parameters optimized:

n_estimators, max_depth, learning_rate

subsample, colsample_bytree, gamma, min_child_weight

📈 **Results**
Best Model – Tuned XGBoost Regressor

R² Score: 0.8225

RMSE: 4.04

MAE: 2.00

✅ The model consistently predicts fares within an average error margin of ~$2, demonstrating high reliability and generalization.

🚀 **Future Enhancements**

1.Integrate traffic and weather conditions for real-time prediction accuracy.

2.Experiment with deep learning models (e.g., LSTMs, Neural Networks).

3.Deploy the solution as a scalable web application for end-user interaction.

🖥 **How to Run**
# Clone repository
git clone : (https://github.com/deeksha27sharma/taxi_ride_fare_prediction)
cd taxi_ride_fare_prediction

## Download dataset 
The dataset used for this project is included in the repository for easy access.

File Location: uber 2.csv

# Launch notebook
jupyter notebook Model_Evaluation_and_Insights_Diksha_Sharma.ipynb

👩‍💻 **Author**

Diksha Sharma
