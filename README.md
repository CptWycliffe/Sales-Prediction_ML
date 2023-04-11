# Sales-Prediction_ML
This Project uses ML to predict sales for items sold at different Favorita stores.

Regression Project (Store Sales -- Time Series Forecasting)

This is a time series forecasting problem. In this project, We'll predict store sales on data from Corporation Favorita, a large Ecuadorian-based grocery retailer.

Specifically, our model will accurately predicts the unit sales for thousands of items sold at different Favorita stores.

The training data includes dates, store, and product information, whether that item was being promoted, as well as the sales numbers. 

Files used in our project

train.csv : The training data, comprising time series of features store_nbr, family, and onpromotion as well as the target sales.

store_nbr identifies the store at which the products are sold.

family identifies the type of product sold.

sales gives the total sales for a product family at a particular store at a given date. Fractional values are possible since products can be sold in fractional units (1.5 kg of cheese, for instance, as opposed to 1 bag of chips).

onpromotion gives the total number of items in a product family that were being promoted at a store at a given date.

test.csv

The test data, having the same features as the training data. We will predict the target sales for the dates in this file.


transaction.csv : Contains date, store_nbr and transaction made on that specific date.

stores.csv :Store metadata, including city, state, type, and cluster.

cluster is a grouping of similar stores.

oil.csv

Daily oil price which includes values during both the train and test data timeframes. (Ecuador is an oil-dependent country and its economical health is highly vulnerable to shocks in oil prices.)
holidays_events.csv

Holidays and Events, with metadata
NOTE: Pay special attention to the transferred column. A holiday that is transferred officially falls on that calendar day but was moved to another date by the government. A transferred day is more like a normal day than a holiday.


A magnitude 7.8 earthquake struck Ecuador on April 16, 2016. People rallied in relief efforts donating water and other first need products which greatly affected supermarket sales for several weeks after the earthquake. We will determine to what magnitude it affected the sales of the products

Data Preparation

Hypothesis & Questions

The questions below are to be answered. Do note that, you are free to draw more hypothesis from the data.

Is the train dataset complete (has all the required dates)?

Which dates have the lowest and highest sales for each year?

Did the earthquake impact sales?

Are certain groups of stores selling more products? (Cluster, city, state, type)

Are sales affected by promotions, oil prices and holidays?

What analysis can we get from the date and its extractable features?

What is the difference between RMSLE, RMSE, MSE (or why is the MAE greater than all of them?)
