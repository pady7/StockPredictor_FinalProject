# StockPredictor_FinalProject
---
Final Project for Spring batch - University of California Berkeley Extension Bootcamp

## Project Synopsis
---
The core idea of the project is to develop a model for a green energy stock.

**Data Sources:** Yahoo Finance, Emph historical stock data

## Team Members
---
* Sam Yang
* Ruimin Ma
* Padmanaban
* Gianne Carranza

## Project Ideas

As a team we have brainstormed quite a few topics such as collecting the data for the H4 Visa holders who have been struggling a lot to find their EAD approvals in long queues to develop a predict data models for underdog teams in **Indian Premier League**. As the team had diversified interests and ideas based on the individual interests, we zeroed on commiting to a project that predicts the stock value of a **Green Energy** company Enphase Energy (Enph). The data points been sourced via yahoo finance and initial ideas been drawn down.

## Project Overview
---
As the need for green/renewable/solar energy is on the historical peak because of ever surging oil and gas prices in the recent past, we've decided to work on a company that has ample opportunities to spike in the coming years. Our goal for this project is to see if we can predict future prices of the ENPH stock using machine learning. We tried modelling and testing with Linear Regression and LSTM to determine the outcome.

# Reason for Project Idea
---
Firstly, the reason the group chose this project idea is because we believe this model can be used in analyzing various stock prices.

Secondly, the dataset mainly contains numerical values and it is easily readable.

Thirdly, the stock market is being considered as major investment portfolio by indiduals and businesses, the model developed in this analysis will help individuals and businesses in making a business decision.

Fourthly, our passion for numerical analysis and data manipulation is a core reason for choosen this project idea.

Finally, to understand the relationship between Tesla revenue, stock prices and Earning Per Share (EPS).

# Question to be answered

Using machine learning algorithms we will train a regression model using historic pricing data and technical indicators to make predictions on future prices.

What we seek to achieve with the data set is to identify trends in the stock market using charts and statistical figures.

# Data Source

The source of data is obtained from yahoo finance.

This data consists of 1536 rows and 7 columns with historical trading data from 2010 - 2020.

There are multiple variables in the dataset – date, Opening price, Highest price that day, Lowest price that day, Adjusted closing price and Trading volume.

The columns Open and Close represent the starting and final price at which the stock is traded on a particular day.

High, Low and Last represent the maximum, minimum, and last price of the share for the day.

Trading volume is the number of shares bought or sold in the day.

## Technology and Systems Used
---
PG Admin

Visual Code Studio
Python
PostgreSQL
PGadmin
Plotly
AWS
Jupyter Notebook
Google Colab
Machine learning
Microsoft Excel
Anaconda
Pandas

# Machine Learning Model

There are four models we trained to make predictions on future stock prices. A simple linear regression model. Linear regression model with technical indicator EMA, Long Short Term Memory Network(LSTM), and Facebook Prophet model.

First module is the linear regression module, which is quite popular for stock market prediction. Linear regression module is defined by using a feature to predict an outcome, and it helps to identify the relationships between a dependent variable and one or more independent variables.

We got historic pricing data for Enphase Energy Inc, from Jan 2017 to March 2022. There are seven columns, most of them easy to understand except for the “Adj Close”. What is Adj Close? It’s actually similar to close values, but the difference is that it considers the factors of dividends, stock splits, and new stock offerings, it is more accurate than the close value considering price prediction.

# Linear Regression Model

First, we converted the “Date” column to a DatetimeIndex. Second, we set Adj Close as our target, and other columns are features. Before we train the module, we plot our data to get a visual picture. It reflects a 5-year price increase, with a relative increase of 250%, and a high volume of shared trade between 2020 and 2021. And then we split the data into features and target, train the module, and get the score of accuracy and mean squared error : the average squared difference between the estimated values and the actual value, for MSE value, the lower the value the better.

![image_name](https://github.com/pady7/StockPredictor_FinalProject/blob/main/Final_project_png/LSTM.png)

When we evaluated the model result,  we realized that it’s not appropriate to use a simple linear regression module to predict stock price like this. Because the linear regression module is effective for time series data, such as identifying trends like seasonality or weather prediction, somehow the variable needs to be related to itself. But when we look at the variables in the stock dataframe, each variable is not that much related, even though it looks like a time series data. The “date” value is not suitable for our independent variable. Because there are many factors that influence the stock price, such as public policy, news, international affairs, etc.,. 


# Linear Regression Model

![image_name](https://github.com/pady7/StockPredictor_FinalProject/blob/main/Final_project_png/LSTM.png)

![image_name](https://github.com/pady7/StockPredictor_FinalProject/blob/main/Final_project_png/linear_regression.png)

![image_name](https://github.com/pady7/StockPredictor_FinalProject/blob/main/Final_project_png/linear_regression2.png)

# Facebook Prophet Model

![image_name](https://github.com/pady7/StockPredictor_FinalProject/blob/main/Final_project_png/facebook_prophet.png)


# Summary


Predicting how the stock market will perform is an enigmatic task to do. There are many factors involved in the prediction, such as supply and demand, market indicators, government fiscal and monetary policy, natural disasters or wars, etc., (Some of them are rational and some of them are irrational behavior, which is hard to forecast.) However, the machine learning models and their strong algorithms still allow us to learn and analyze the pattern and behavior of the stock prices. We resonated with this idea through practicing the linear regression model with EMA indicators and the LSTM model during our project. 

The models we trained are not that perfect, for example, we should have built more convincing relationships between independent and dependent variables, make comparisons among each model we trained, and imported multiple stocks datasets from other green energy companies to validate our models.,. However, the models we’ve trained so far still provided an effective way and rich resources to help us understand the trends of the stock price as well as promote us to further explore the factors that will influence the stock market.


## Locations of Project Deliverables:

| Objective | Location |
|-----------|-----------|
|Presentation| [Google Slides]|
|Exploratory Analysis code | GitHub Master Branch -  |
|Machine Learning code and output | GitHub Master Branch - Resources folder |


## Presentation
The link to the presentation on Google Slides can be found [here](https://docs.google.com/presentation/d/1p80bp2mV4zhRoJfl8g2sdp7gDon-e-Cy/edit?usp=sharing&ouid=106759923296677285620&rtpof=true&sd=true)
