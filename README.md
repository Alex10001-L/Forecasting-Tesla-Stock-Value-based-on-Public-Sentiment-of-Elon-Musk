# Forecasting-Tesla-Stock-Value-based-on-Public-Sentiment-of-Elon-Musk
**Note- This project was accomplish with 3 other individuals. I was responsible for scraping Reddit comments, forecasting Tesla stock prices, and performing correlation analysis, which is why only these specific code sections are included.**

                                                      Executive Summary

Our group's collective interest inspired our project to understand how public sentiment may or may not affect stock prices. Given that Tesla has been one of the most popular topics on social media such as X, YouTube, and Reddit, we were interested in understanding how public sentiment on Elon Musk and Tesla has changed over time in the last 18 months. During the window we observed (October 2023 - April 2025), several major events involving Elon Musk and Tesla occurred, such as the launch of the Tesla Cybertruck and Elon Musk being appointed to lead the Department of Government Efficiency (DOGE). 

The study aims to determine whether sentiment extracted from Elon Musk-related social media posts correlates with Tesla’s stock price behavior, and if so, to what extent this relationship can improve stock price forecasting accuracy.

                                                      Research Questions:
1. "What is the projected Volume Weighted Average Price (VWAP) and closing price of Tesla stock at the end of May 2025? **Note-The time we made this forecast was on April 2025**
2. How strong is the correlation between Tesla’s stock value (VWAP and closing price) and public sentiment toward Elon Musk?
                                                      
                                                      Data:

1. Tesla stock data will be of two-year period (October 2023 to April 2025) that we scraped directly from the internet.
2. Comments from Reddit, YouTube, and Twitter/X are scraped from the internet and filtered to exclude any posts or comments mentioning Elon Musk. This process is used to gather information on public sentiment.


                                                        Modeling Approach:

The predictive model for forecasting will be done using a Long Short-Term Memory (LSTM) recurrent neural network, as it can capture long-term dependencies and temporal patterns in sequential data. The model was trained on historical stock data augmented with daily sentiment scores to evaluate whether incorporating social media sentiment improves forecasting performance. The evaluation metric to judge its predicitve accuracy will be Root Mean Sqaured Error (RMSE).

                                                      Technical Report
https://docs.google.com/document/d/1tYTXHhVcIJsSIotTKGow3tdc1VsSGb5oYk6KhjMijLc/edit?usp=sharing 

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------

Coding Language: Python
