# FlightPricePrediction using Machine Learning

A machine learning project to predict the price for domestic flights in India with deployment.

### Problem Statement
The task is to get an estimate of the price of flights in India given the details about the flights like source,destination,etc.

### Data
The dataset used is available on kaggle.
The dataset contained information like source,destination,departure date and time,arrival date and time , stops and price as target variable and data preprocessing was required to convert this data to numerical digits and breaking of certain features like date to month and day , time to hours and minutes and one hot encoding for sourse and destinations.

### Performance Metric
Accuracy score is used to compare the performance for different algorithms and finally XGBoost is used as it gave the best results.

### Deployment
This webapp is deployed on Heroku Cloud platform.
Link to access the app - https://flight-fare-prediction112.herokuapp.com/
