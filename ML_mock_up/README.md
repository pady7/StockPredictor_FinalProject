# **StockPredictor(FinalProject_First_Week)**
---
Final Project for Spring batch - University of California Berkeley Extension Bootcamp


## **Ideas Brainstorming**

As a team we have brainstormed quite a few topics such as collecting the data for the H4 Visa holders who have been struggling a lot to find their EAD approvals in long queues to develop a predict data models for underdog teams in **Indian Premier League**. As the team had diversified interests and ideas based on the individual interests, we zeroed on commiting to a project that predicts the stock value of a **Green Energy** company Enphase Energy (Enph). The data points been sourced via yahoo finance and initial ideas been drawn down.

## **Project Overview**
---

Selected Topic - *green energy stocks*

**Overview:** 

Green energy stocks have been enormously affected since the United States officially rejoined the Paris Agreement on climate change on January 20, 2021. Our team selected this topic in order to analyze how the green energy stocks were affected when the US rejoined the Paris Agreement as well as to forecast its future market value. We will explore our topic through analyzing the stock trend of Enphase Energy, Inc. (ENPH).


## **Team Members**
---
* Sam K Yang
* Ruimin Ma
* Padmanaban
* Gianne Carranza


## **Questions we would like to explore:**

*1. Given the data available, can we expect the ENPH price to increase or decrease in the coming years? If it increases, what is the growth rate?*

*2. Does the quarterly earnings play a determining factor in the price of the stock? Higher than historical value?*

*3. Comparative studies to another green stock by taking annual revenue, green energy ETF/stocks to give a baseline to measure.*

*4. Comparison to open versus closing values, volume per day and how it affects the price.*



## **Technology and Systems Used**
---
Technologies: tableau, SQL
Languages: python, pandas
Tools: jupyter, GitHub
Algorithms: Machine Learning (Linear Regression, LongShort-Term Memory(LSTM))


## **Mock up for Machine Learning Application**

We will examine the stock price of Enphase Energy, Inc (ENPH) as reported by the National Association of Securities Dealers Automated Quotations (NASDAQ). The stock price data will be supplied as a Comma Separated File (.csv), that may be opened and analyzed in "linear regression" module and Long Short-Term Memory (LSTM). 

ENPH’s stocks are listed on NASDAQ and their value is updated every working day of the stock market. It should be noted that the market does not allow trading on Saturdays and Sundays, therefore there is a gap between the two dates. The Opening Value of the stock, the Highest and Lowest values of that stock on the same days, as well as the Closing Value at the end of the day, are all indicated for each date.


## **Notes from group discussion**

**Notes 3/8:**

- Focusing on closing value, make it as granular as possible based on what data is available (e.g. closing value, hourly price, etc.)
- If machine learning is inaccurate in predicament, can highlight the possibility of why it’s inaccurate due to outside sources
- Using linear regression model 
- Ryan’s suggestion: think about what database might look like (what the data contains), find other data sets with time stamps to match to stock data that are relevant (API to pull this type of data?,  module 10 stuff?)
- I.e. this event may have correlated to the stock price/ data pt is highlighted by an event that it affected its price
- Can reduce the time instead of looking at the whole dataset
- Presentation should take ~10 min. Suggest a maximum of 12 min. Each slide should take roughly 1 to 1 ½ min to present. Max 15 to 20 slides. 

**Database notes:**

- Create postgre and have that file and import clean data with machine learning
- Switch from jupyter notebook to google collab to work on remaining portions
   Can share, edit, add together for rubric



**Notes 3/10:**

- Bring in another data set with a timestamp considering that the amount of data points are low. 
- Ryan’s suggestion: Can use another stock to do a comparative study and to give more room to play with the data. E.g. use gas stock prices and narrow it to the time frame to the green stock and see if there’s any correlation. Merge data sets
- With machine learning, when gas stock goes up/down, what happens to the green stock? Or predictability on how accurate it is?



