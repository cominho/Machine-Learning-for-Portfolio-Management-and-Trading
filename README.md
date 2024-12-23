# Machine Learning for Portfolio Management and Trading

The aim of our project is to use data from speeches by FED officials, scraped from the site, to determine a signal about economic conditions. After using NLP techniques to construct this signal, we deploy a RandomForest model to predict the interest rate of 10Y Treasury bills. Features include our indicator, as well as other macro indicators useful for prediction. We then develop a simple trading strategy, which consists of going long if our model predicts a rise, and going short if it does not.
