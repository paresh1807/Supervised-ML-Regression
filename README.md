# Supervised-ML-Regression
YES BANK STOCK CLOSING PRICE PREDICTION.

**PROJECT SUMMARY-**
Yes Bank was a very reputable bank till 2018. After 2018, the bank came under the umbrella of risk-inflated banks because of the fraud case by Rana Kapoor. This project would help not only yes bank but all those banks who want to predict their future and are in a conundrum for their future. So Machine Learning is helping us to resolve the issue of all those companies and firms who want to gather some courage in order to survive in the market for a longer time. By predicting the price with the acquaintance of Machine Learning especially linear Regression and other regressors, which helped firms and companies to sustain in the market. In this project, the monthly Open, Close, Low, and High prices of Yes Bank stock have helped to train the model on which learning occurred and then the respective prediction occurs.

**PROBLEM STATEMENT-**
Yes Bank is a well-known bank in the Indian financial domain. Since 2018, it has been in the news because of the fraud case involving Rana Kapoor. Owing to this fact, it was interesting to see how that impacted the stock prices of the company and whether Time Series models or any other predictive models can do justice to such situations. This Dataset has the monthly stock prices of the bank since its inception and includes closing, opening, highest, and lowest stock prices of every month. The main objective is to predict the closing stock price of the month.

**VARIABLE DESCRIPTION-**
In the given dataset there are 185 rows and 5 features, Features descriptions are as follows-

**Date**-: Date denotes the date of investment(date contains month and year for a particular price.)

**Open**-:  It is the price at which a stock started trading.

 **High**-: It is the highest price at which a stock is traded during a period.
 
 **Low**-: It is the minimum price at which a stock is traded during a period.
 
 **Close**-: The closing price refers to a stock's trading price closed at the end of a trading day. It's a dependent variable that we need to predict from our respective ML models. The closing price is calculated as the weighted average price of the last 30 minutes, i.e. from 3:00 PM to 3:30 PM in case of equity.

 **OBJECTIVE-**
 The objective of this project is to predict the yes bank stock closing price of the month which includes the  following steps-
 1. Loading the data into a  data frame.
 2. Cleaning the data.
 3. Exploratory analysis and visualizations.
 4. Feature Manipulation and  Selection.
 5. Train Test Split.
 6. Model Implementation.
 7. Selecting the best model.
 8. Model Deployment.

 **Conclusion-**
 
 **Closing Price** of a stock refers to the final price at which the stock is traded on a particular stock exchange on a given trading day. It is the last price at which the stock is bought or sold during the trading session.

*Importance:* The closing price is an important metric used by investors, analysts, and traders to evaluate a company’s financial health, market value, and stock performance. It is also used to calculate other important metrics such as the daily price change, market capitalization, and trading volume.

For an *Average Investor:* An average investor sees investing in stocks for long-term purposes and in premium stocks that have proved to be quality and high-performing stocks over the years. For such investors, the daily closing price may not hold as high importance as for an average trader.

For a *Traders:* For traders and analysts, the information on the closing price of stocks is essential to make sure that they make sound trading decisions and maximize returns on their portfolios.

**Models Implemented**
* I have implemented six models/Algorithms- Linear Regression,Lasso Reguralization,Ridge Reguralization,Elastic Net, Random Forest Regressor, XG BOSST Regressor.
* The best performing model to predict the closing stock price of yes bank is **Ridge Reguralization** having training and testing accuracy as 95% and 94% respectively in untuned condition having lowest *RMSE*(.219), with cross-validation and hyperparameter tuning(*Tuned Model*) its training and testing accuracy is 97% and 94% respectively which tends to generalized fitting and prone to slight-risk of overfitting.


* All *Independent Features*(High,Low,Open) are Strongly correlated with each other as well with the *depenedent Feature*(Close) also.
* According to the best performing model Feature **Low** is of utmost importance.

* Evaluation Metrics used to choose the best performing model is *r2_score* and *RMSE*.

 *The results indicate adopting supervised Learning Algorithms to identify stock manipulation using a labeled dataset based on a Fraud case is promising*.

    



   

