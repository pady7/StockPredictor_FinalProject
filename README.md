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

# Machine Learning Model

The first review of the data was done using excel to access the data characteristics.

We will load historic pricing data into a Pandas’ DataFrame for the Linear Regression model.

We will train a simple linear regression model using moving average as a predictor for the closing price.

We will analyze the accuracy of our model, plot the results, and consider the magnitude of our errors.

We will be using python and scikit-learn to present a provisional machine learning model that stands in for the final machine learning model.

This model will take data from the provisional database and output labels for input data.

The target is closing stock price, the data split into training and test set (80, 20).

Four models Autoregressive Integrated Moving Average (ARIMA), Facebook Prophet, Long short-term memory (LSTM) and Linear Regression will be used for the machine learning.

The model with the best result (magnitude of errors, accuracy) will be selected for final deployment.

# Linear Regression Model


Machine Learning model been tested and ran thru successfully. 
Ran a different model to ensure the outcome.
Found the observations did not deviate much.
All 3 models worked the way we expected it to be.

## Technology and Systems Used
---
PG Admin

![Screen Shot 2022-03-10 at 8 39 47 PM](https://user-images.githubusercontent.com/92561003/157803342-4166d300-ccae-40fd-8035-231ef251fed5.png)

Google Slide <br/>
Jupyter Notebook


## Locations of Project Deliverables:

| Objective | Location |
|-----------|-----------|
|Presentation| [Google Slides]|
|Exploratory Analysis code | GitHub Master Branch -  |
|Machine Learning code and output | GitHub Master Branch - Resources folder |


## Presentation
The link to the presentation on Google Slides can be found [here](https://docs.google.com/presentation/d/1p80bp2mV4zhRoJfl8g2sdp7gDon-e-Cy/edit?usp=sharing&ouid=106759923296677285620&rtpof=true&sd=true)
