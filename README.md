# BT4222 - Prediction of Earnings per Share for Meme Stocks
## Disclaimer
This GitHub repository primarily showcases the portions of the project that I solely contributed and can confidently claim as my work. Since this project was a collaborative effort, some components or results may not be entirely reproducible when taken out of the group context. Please keep this in mind when exploring the content presented here. If you have any questions or need further clarification, feel free to reach out. Thank you for understanding.

## Introduction
We would like to use a combination of financial data and text-based sentiment analysis of retail investors' online communications to predict quarterly earnings announcements’ performance to make investment decisions to profit on the large movements of the stock prices following the earnings announcements.

With the theory that the reported EPS of a “meme stock” is a function of its financial performance and its online public sentiment, we have identified 5 sources to form a composite dataset, namely (1) Reddit Posts (2) Twitter Tweets (3) Earnings Calls (4) Company Financials and (5) Google Analytics Trends. 
We selected the top 100 stocks that were most frequently mentioned in Reddit posts in the past year. Our data collection time frame is 3 years, which is about the time when retail interest in investing grew exponentially.

Baseline Binary Classification Models - Logistic Regression & SVM (1 for EPS beat and 0 for miss).  
Possible Models: Decision trees (XGBoost and LightGBM), Neural networks.  
Model Evaluation: Measure the F1-Score and AUC-ROC to determine model performance.
