Real Estate Price Prediction (Linear Regression vs Random Forest)
Overview
This project builds and compares machine learning models to predict house prices using real estate data. The goal is to understand how different models perform on structured tabular data.
Two models were used:
•	Linear Regression (baseline model) 
•	Random Forest Regressor (advanced model) 
Dataset Description
The dataset contains real estate property information including:
•	House age 
•	Distance to nearest MRT station 
•	Number of convenience stores nearby 
•	Geographic location (latitude & longitude) 
•	Transaction date 
•	House price per unit area (target variable) 

Project Workflow
1.	Data loading and inspection 
2.	Data cleaning (checked duplicates and missing values) 
3.	Exploratory data analysis 
4.	Feature selection 
5.	Train/test split 
6.	Model training: 
o	Linear Regression 
o	Random Forest Regressor 
7.	Model evaluation 
8.	Performance comparison 

Models Used
Linear Regression
A simple baseline model that assumes a linear relationship between features and house prices.
Random Forest Regressor
An ensemble model that captures non-linear relationships using multiple decision trees.

Model Performance
Model	MAE	RMSE
Linear Regression	5.41	7.39
Random Forest	3.87	5.64

Key Insights
•	Location-related features (distance to MRT, latitude, longitude) strongly influence house prices 
•	Random Forest performs better than Linear Regression due to its ability to capture non-linear relationships 
•	Linear Regression provides a good baseline but is less flexible 

Visualization
•	Actual vs Predicted scatter plot was used to evaluate model accuracy 
•	Random Forest predictions generally align more closely with actual values 

Technologies Used
•	Python 
•	Pandas 
•	NumPy 
•	Scikit-learn 
•	Matplotlib 
•	Jupyter Notebook 

How to Run
pip install pandas numpy scikit-learn matplotlib
Open the notebook:
jupyter notebook

Conclusion
This project demonstrates a complete machine learning workflow from data preprocessing to model comparison. It highlights how ensemble methods like Random Forest can improve prediction accuracy compared to simple linear models.

