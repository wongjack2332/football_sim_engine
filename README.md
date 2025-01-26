This is a football simulation engine using linear regression to predict and generate premier league results using 23/24 season data.

the ipynb file sets up for a 37 game sample size, to predict the 38th game but can be easily changed to any other number of games.

Since expected goals are the predicted value, a poisson distribution is used to generate results through a random variate, however, in real life, teams deviate by their xG a lot, some more and some less than their xG, so future changes include factoring in the xG and GF difference by predicting the difference and using it as a predictor.

requires jupyter notebook
