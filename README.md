# Predicting House Prices with Linear Regression
 Project Overview
 This project demonstrates how to build a machine learning model using **Linear Regression** to
 predict house prices based on multiple numerical features.
 It includes steps from data loading to model evaluation and visualization.--
## 
 Dataset
 The dataset contains the following columns:- area (sq ft)- bedrooms- bathrooms- stories- parking- age- price (target)
 You can upload your dataset in Google Colab using:
 ```
 from google.colab import files
 uploaded = files.upload()
 ```--
## 
 Key Steps in the Project
 ### 1. Data Loading
 Loading CSV files and reading them using pandas.
### 2. Data Exploration & Cleaning- Checking dataset structure- Handling missing values- Generating statistical summaries- Plotting correlation heatmaps
 ### 3. Feature Selection
 Selecting relevant columns for model input and target.
 ### 4. Model Training
 Using **Scikit-Learn LinearRegression** to train the predictive model.
 ### 5. Model Evaluation
 Metrics used:- Mean Squared Error (MSE)- Root Mean Square Error (RMSE)- R² Score
 ### 6. Visualization
 Plot:- **Actual vs Predicted values**--
## 
 How to Run This in Google Colab
 1. Open Google Colab: https://colab.research.google.com
 2. Upload the dataset file (`house_prices.csv`)
 3. Copy and run the complete project code provided
 4. Visualize model performance and interpret results--
## 
 Learning Objectives- Understand linear regression concepts- Learn end-to-end ML pipeline- Evaluate machine learning models- Visualize regression predictions
