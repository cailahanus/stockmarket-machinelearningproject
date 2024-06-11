# stockmarket-machinelearningproject

**Topic: Stock Price Prediction Analysis**

**Team members:** Caila Hanus, Dani Bar-lavi, Kayode Ayenioye, Paulette Petracco

**Main Research Questions:**

* Predict stock market movement

* Where it's going to be tomorrow? Next week? Next year?

* Assessing volatility/risk of stocks over the last year

* Sort stocks into high, low, medium volatility

* Sentiment analysis of financial news and social media impact on stock price prediction


Dataset: [https://www.kaggle.com/datasets/hchsmost/test-dataset](https://www.kaggle.com/datasets/hchsmost/test-dataset)

**Project Description:** 

Our project will focus on the dynamic and volatile nature of the stock market, which presents both opportunities and risks. We will aim to predict the movement of stock prices and assess the associated risk levels. With utilization of machine learning techniques to enhance stock market prediction accuracy.


**How we are approaching the use of the data:**

* We have a total of 77 stocks to choose from

* We are each pulling random stocks to use

* Going back 5 years

* Pivot to 10 years if more data is needed for the model

**Paulette:**

In looking at the Food and Travel and Health and Beauty sectors, I was able to: 

1. **Load and Combine Stock Data:** Read multiple CSV files from a directory, add a ticker symbol  
        column, and concatenate them into a single DataFrame.

2. **Filter Data:** Convert the date column to datetime format and filter the data for the last ten 
        years.

**Analyze Specific Stocks: For each stock in the specified list:**

    * Prepare the data by setting the date as the index and creating features such as "Previous Day 
      Close" and "Volume Difference".

    * Split the data into training and testing sets.

    * Normalize the data.

    * Build and train a neural network model to predict stock prices.

    * Make predictions and calculate the mean squared error (MSE).

    * Predict future stock prices for the next 60and 120 months.

    * Save Predictions and MSE: Save the predictions and MSE results to CSV files in specific 
      directories.
