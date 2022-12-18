# Machine-Learning-Projects-With-Python
This repo contains Machine Learning projects

<hr>

![](https://d2r55xnwy6nx47.cloudfront.net/uploads/2022/02/SCALING_NETS_2880x1620_Lede.svg)

<hr>

# Machine Learning Projects

<hr>

 - ## Walmart store sales forecasting | Random Forest | XGBoost | Hyper parameter tuning ([<img src="https://img.icons8.com/fluency/48/000000/code.png"/>](https://jovian.ai/raghu-rayirath/walmart-store-sales-forecasting-v4)):
    - Problem Statement: The dataset contains the historical sales data for 45 Walmart stores located in different regions. Each store contains a number of departments,We are forecasting department-wide sales for each store. In addition, Walmart runs several promotional markdown events throughout the year.These markdowns precede prominent holidays, the four largest of which are the Super Bowl, Labor Day, Thanksgiving, and Christmas. The weeks including these holidays are weighted five times higher in the evaluation than non-holiday weeks. In this problem, we are modelling the effects of markdowns on these holiday weeks in the absence of complete or ideal historical data.
    - `Dataset`: The dataset contains `420K+ observations and 16 features` (store, department, date, weekly_sales, isholiday, etc.) of the Walmart sales data.
    - pre-processed data from over 420k+ records with over 16 features to forecast Walmart sales data.
    - performed data cleansing, data imputation, encoding, scaling, and feature engineering to improve the model's performance and reduce the loss.
    - Libraries used: Pandas, Numpy, Sklearn, Matplotlib, and Seaborn. To fully comprehend the data, use Plotly to visualise it and its features.
    - Machine learning models: `Random Forest regressor`, `XGBoost regressor`.
    - The model achieved an accuracy of `Adjusted R^2 = 97.29%` after hyperparameter tuning.
    - This model was entered into the `Kaggle competition and placed in the top 15% of the leaderboard`.
    - Eg: Hyper-parameter tuning sample 
    - <img width="543" alt="image" src="https://user-images.githubusercontent.com/41443395/206430341-c3c15420-daae-4ea1-bb40-81096c2b64d4.png">
    - Eg: Results Sample
    - <img width="545" alt="image" src="https://user-images.githubusercontent.com/41443395/206429971-f5c51992-7f45-4c9c-8767-c3b23c7f4f0c.png">

<hr>

 - ## New York City Taxi Fare Prediction ([<img src="https://img.icons8.com/fluency/48/000000/code.png"/>](https://nbviewer.org/github/Raghu-murugankutty/Machine-Learning-Projects-With-Python/blob/main/New%20York%20City%20Taxi%20Fare%20Prediction%20_%20Random%20forest%20_%20XGB.ipynb)):
    - `Problem Statement`: The dataset contains the record of taxi trips in New York City. Our objective is to create a model that will accurately estimate the fare amounts of trips in the test dataset. Accuracy is measured by the root-mean-square error.
    - `Dataset`: The dataset contains `5.5 million observations and 8-features` (fare_amount , pickup_longitude , pickup_latitude, dropoff_longitude    dropoff_latitude, passenger_count, etc.) of taxi trips in New York City.
    - pre-processed data from over 10% of the 5.5 million records with over 8-features to accurately estimate the fare amounts of taxi trips.
    - performed data cleansing, data imputation, encoding, scaling, and feature engineering to improve the model's performance and reduce the loss.
    - Libraries used: Pandas, Numpy, Sklearn, Matplotlib, and Seaborn. To fully comprehend the data, use Plotly to visualise it and its features.
    - Machine learning models: `Random Forest regressor`, `XGBoost regressor`.
    - A gradient boosting decision tree model with `RMSE obtained 3.23`. 
    - This model was entered into the `Kaggle competition and placed in the top 30% of the leaderboard`.
    - Eg: Please find below the snapshot of learning rate parameter tuning.
    - <img width="490" alt="image" src="https://user-images.githubusercontent.com/41443395/206457525-df7a07e1-27b3-4c03-a883-c20c3e5b9ca6.png">
    
<hr>
