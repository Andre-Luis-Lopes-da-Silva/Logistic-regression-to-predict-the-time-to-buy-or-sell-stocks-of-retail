# Logistic-regression-to-predict-the-time-to-buy-or-sell-stocks-of-retail
This is a predictive model for trade of stocks of retail using macroeconomic indicators 

INTRODUCTION

Logistic regression is one of the most popular Machine Learning algorithms, which comes under the Supervised Learning technique. It is used for predicting the categorical dependent variable using a given set of independent variables.

The retail sector consists of all companies that sell goods and services to consumers and macroeconomic scenarios are multi-year projections of economic variables. The retail sector is sensitive to macroeconomic variations, especially when there are low gross domestic product (GDP) projections, high interest rates and high inflation rates.

Therefore, the aim of this study was to establish a model using logistic regression to predict the macroeconomics scenario to buy or sell stocks of retail sector.

MACROECONOMIC INDICATORS AND RETAIL STOCKS

Lojas Renner (LREN3) was chosen to be a representative stock of the retail sector of companies traded on B3 (brazilian stock exchange). The indices Broad National Consumer Price Index (IPCA), Special System for Settlement and Custody (selic), Central Bank Economic Activity Index (IBC-Br), Broad Retail Trade Confidence Index (ICOM), Future Expectations Index, Dollar (exchange), Consumer Stock Index (ICON) and Ibovespa Index (IBOV) were initially analysed by correlation. See the file (https://github.com/Andre-Luis-Lopes-da-Silva/Artificial-Neural-Network-to-predict-the-macroeconomics-scenario-to-buy-stocks-of-retail-sector/blob/main/correla%C3%A7%C3%A3o_repository.ipynb). Data from during 10 years were used (2011-2021).

The indicators 'ipca', 'expectativa', 'icom', 'IBC-Br' and 'selic' were removed to better adjust to the model.

STOCK TREND

The trend of the stock was considered only bullish or bearish (binary classification). When the trend was sideway and followed by a uptrend, the trend was considered uptrend because it would be a good opportunite to buy. This same reasoning was used when there was a lateralization followed by a bearish trend.

CONCLUSIONS

The model needs to be improvement, the metrics obtained were:

Accuracye :  0.69

Precision :  0.68

Recall ...:  0.89

F1 Score .:  0.66
