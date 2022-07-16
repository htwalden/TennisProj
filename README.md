# Predicting Tennis MAtch Winners and Losers
## Hunter Walden, Kevin Mitchell, Jason Myslewski
### 16 Jul 2022
#### George Mason University

Is it possible to determine if a tennis player is a winner or a loser based on their match statistics? We set out to determine if this was possible using data from major tennis tournament matches. There are a number of statistics collected on each tennis player as a result of their match. Important statistics include set scores, total points won, winning shots, unforced errors, net points won, break points won, first and second serve percentages and net points won, among many others. In order to find a solution to our question, we determined what statistics were most important and used those for predictive analysis.

The dataset used in this project was derived from the UCI repository. We downloaded both men's and women's match data from all four major tennis tournaments. Overall we had a combined dataset of over 1800 individual records. Each record contained the statistics for a discrete tennis match for both players. Our data cleaning process included renaming columns, dropping unnecessary columns, removing or imputing missing data, removing outliers, and concatenating datasets. We ran classification models to determine predictive ability on match outcome. We examined the output of three different models. We chose Naive Bayes, Logistic Regression, and K-Nearest Neighbors. Overall we were able to predict a winning or losing player based on 4 features with 84% accuracy.
