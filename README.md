# Calories-Burnt-Prediction_ML_Python
This project helps to predict how many calories you would burn during a specific duration.It takes some parameters such as your duration of exercising, average heart beats per minute, body temperature, height and weight of person and use XGBoost Regressor model to predict the calories burnt.

XGBoost is an efficient implementation of gradient boosting that can be used for regression predictive modeling

## Dataset source : 
Kaggle - 2 CSV Files 

    a. Exercise.csv  : https://www.kaggle.com/datasets/fmendes/fmendesdat263xdemos?select=exercise.csv
    b. Calories.csv  : https://www.kaggle.com/datasets/fmendes/fmendesdat263xdemos?select=calories.csv
    
    
## Libraries to install 
Numpy, Pandas, Scikit-Learn, Matlotlib, Seaborn, PyXGBoost


## Platform to Implementation
We use Jupyter Notebook to implement this project

## Workflow
•	First step : collect data .
We need data to train the ML model, so that it can find out what is the amount of calories going to burn

•	Second step: Data Preprocessing – We clean the data before feeding into MLmodel

•	Third Step : Data Analysis   (understand dataset better , which enable make better predictions)
Use some visualisation techniques to plot data in plots n graphs


•	Train Test Split : Split the data into training dataset and testing dataset
Train data – train our ml model
Test data : Evaluate/Test data

•	After split, we need to train our ML Algorithm, in this case we are going to use : XGBoost Regressor(ml model).
(XGBoost Regressor is a regression algorithm that is an analysis which is a statistical technique to model the connection between a dependent (target) and independent (predictor) variables with one or more unbiased variables. In machine learning the XGBoost algorithm performs well since it has robust handling of many variety of data types, relationships, distributions, and the many hyperparameters that you can fine-tune. XGBoost regressor can be used for regression, classification for both binary and multiclass, and ranking problems.)

We train XGBoost regressor with training data.
We use regressor because this is an example of regression problem


•	Evaluate the model with test data. 
We use Mean Absolute Error to check the accuracy of our prediction. In our case we got a value 1.48 for MEA which means our prediction is best and XGBoost Regressor is a good ML model
![image](https://user-images.githubusercontent.com/45625862/182100947-5560c745-3826-464a-a7d9-d1c9b26818c5.png)





