# Forecasting Future Sales

### Business Objective
Every retailer must stay on top of planning activity to stand the demand of goods based on needs.

A highly accurate demand forecast is the only way retailers can predict which goods are needed for each store location. This will also ensure high availability for customers while maintaining minimal stock risk and support capacity management, store staff labour force planning, etc.

Building a forecasting model to predict a store item demand is an uphill task as there are multiple external factors like store’s location, seasonality, changes in a store’s neighbourhood or competitive situation, a significant variation in the number of customers, and goods, etc. With this huge amount of data, no human planner could consider the full range of potential factors. However, deep learning makes it easier and considers these factors at a detailed level, by individual store or fulfilment channel.

I used LSTM, which is very suitable for handling time-series data and widely used for forecasting purposes.


### Dataset description
train.csv — Training data

test.csv — Test data

The fields included in the dataset are as below:

date — Date of the sales data.

store — Store ID

item — Item ID

sales — The count of items sold at a particular


### Tech stack:-
###### PySpark Dependencies: PySpark.ml, PySpark.sql

###### Python Dependencies: Keras, NumPy, Pandas, sklearn, Matplotlib, LSTM

I used PySpark to handle real-time streaming data (as the sales of the items and goods have to be addressed in real-time) and build highly scalable models.

#### Key learnings:-
[1] Got hands on experience of the concept of forecasting

[2] Understood architecture of LSTM and implementation in forecasting

[3] Dealt with seasonality in forecasting
