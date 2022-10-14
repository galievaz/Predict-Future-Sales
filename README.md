# Predict-Future-Sales
Tha nanodegree capstone project

This challenge serves as final project for the "How to win a data science competition" Coursera course.

The time-series dataset consisting of daily sales data, kindly provided by one of the largest Russian software firms - 1C Company. 

The dataset and additional information can be found here:
(https://www.kaggle.com/competitions/competitive-data-science-predict-future-sales )

The main goal is to predict total sales for every product and store in the next month. In context of marketing it’s very important as soon as possible know to make business decisions that can bring more profits and see insights in customer behavior for effective investing and optimizing of store. Nowadays there are a plenty of tools that can enable forecast in market or open-source, depending on the level of customers and budget. By using of new techniques and approaches of machine learning libraries it’s possible easy and fast to analyze data, create statistics and make predictions.

Motivation: Time-series forecasting is one of machine learning tasks and as my next activity in my job I have project with time-series forecasting. This usecase provides a good opportunity to practice received skills and knowledge from the course and my background to try it out and get a new experience.

Problem statement:

To predict the total amount of products sold in every shop and a total number of sales for each id product based on historical sales data.

Evaluation metrics:

As a metrics for evaluation of predicted target values and actual target values in test data was used root mean squared error (RMSE).
The final value as in the benchmark (RMSE=1.2)

Solution statement:

The provided code will be written on Python3 in Jupyter notebook with using classic data science libraries such as pandas, scikit-learn, matplotlib for plotting and visualization, catboost, xgboost, lightgbm. The type of problem is regression, that means that we need to estimate output and decide which features can impact to target. 
