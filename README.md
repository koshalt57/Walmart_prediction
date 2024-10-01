# Walmart_prediction

Problem Statement 
A retail store that has multiple outlets across the country are facing issues in managing the inventory - to match the demand with respect to supply. You are a data scientist, who has to come up with useful insights using the data and make prediction models to forecast the sales for X number of months/years. 

Project Objective 
The objective was to forecast the weekly sales for each Walmart store for the next 12 weeks using a 
Random Forest Regression model. 

Data Description 
The walmart.csv contains 6435 rows and 8 columns. 

Data Pre-processing Steps and Inspiration  
Loading the Data, Handling Missing Data, Feature Selection, Select relevant columns for prediction: 
Store, Fuel_Price, Temperature, CPI, Unemployment, and Holiday_Flag as input features (X),
and 
Weekly_Sales as the target variable (y). 

Choosing the Algorithm for the Project 
Evaluating the model on the given data set using appropriate metrics (e.g., Mean Squared Error, R² 
score). 

Motivation and Reasons for Choosing the Algorithm 
Random Forest Regression because it Balances accuracy and interpretability: While not as 
interpretable as linear models, it is more understandable than neural networks. Handles complex, 
non-linear relationships: It is excellent at capturing the effects of temperature, fuel price, holidays, 
and CPI on sales. 

Model Evaluation and Techniques 
Train-Test Split, to test the model's ability to generalize to unseen data. Split the dataset into two 
parts: Training Set: Used to train the model. A typical ratio is 80% for training and 20% for testing. 

Inferences from the Same 
If Random Forest gives lower RMSE, MAE, and higher R² than Linear Regression on the test set, it is 
likely the better model for predicting Walmart sales. 

Future Possibilities of the Project 
This project has the potential to evolve well beyond simple sales forecasting. By integrating 
additional factors, adopting advanced time series models, and broadening the focus to include 
customer segmentation, real-time monitoring, etc. Walmart can enhance its decision-making 
process. These improvements will boost business performance, increase customer satisfaction, and 
streamline operations.
