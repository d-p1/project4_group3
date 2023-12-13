# Project 4 : Stocks: What Would My Rich Dad Do? 


## BACKGROUND:
Welcome to a journey into the dynamic world of stocks, where we embark on an exploration of financial data and market trends with the overarching question in mind: What would my rich dad do? In this project, we delve into the intricacies of stock market behavior, employing a multifaceted approach to analyze and predict stock trends obtained from YAHOO Finance.

## Key Objectives:
1. Find the TSLA stock data using YAHOO Finance.
2. Use Postgres to retrieve and organize the dataset.
3. Pandas will be used to analyze the data.
4. Use unsupervised machine learning to optimize and predict the TSLA trend with at least 75% classification accuracy. 

## What is the Stock Market?

A stock market is a public market where you can buy and sell shares for publicly listed companies. The stocks (also known as equities) represent ownership stakes in the company. The stock exchange is the mediator that allows the buying and selling of shares.


  ![Picture1](https://github.com/d-p1/project4_group3/assets/134445591/8eb0b0fc-28ef-43e5-8f05-9b18d7a89eaa)



Tesla is a US automotive company that officially became a part of S&P 500 Index on December 21,2020. The S&P 500 or Standard & Poor’s 500 Index is a market capitalization-weighted index of the 500 largest US places open. It is considered to be the best indicator of wide-ranging US stocks. With increasing shares in Tesla, the market value has increased to around $775 billion. There are many who are skeptical of Tesla’s company performance and feel the stock is overvalued.


Now with the recent release of the Cybertruck, we ask a question: how will Tesla's stock performance change over 180 days? 

Using machine learning, we will predict the trend for the TSLA stock and determine whether the stock is truly overvalued or not.

# Analysis:

## After analyzing the historical data and predicting the TSLA stock performance over 60 days, we noticed:

### Pros:
* Our initial goal was to get at least 75% classification accuracy but we ended up getting a 56% accuracy
* RSME of 7.37 is more accurate than RSME of the initial test, 12 when we were testing over 180 days and 10 epochs
* There is a positive correlation between the days of prediction and RSME value. The higher number of days we test, the closer to zero the RSME becomes, meaning our model is more accurate 

### Cons:
* Although our data had a 56% accuracy, the prediction close to the valid closing price
* Stock market in general is hard to predict, wouldn't we all be billionaires if we could predict with 100% accuracy?

Overall, Tesla actual performance exceeds the machine learning predictions, proving that the stock is not overvalued to the dismay of critics and may continue performing well with the recent release of the Cybertruck.


 
