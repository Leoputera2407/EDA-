# 2017-2018-NBA-Regular-Season-Analysis
Exploratory Data Analysis of 2017/2018 NBA Regular Season




####Machine Learning
I trained 6 different machine learning classification models to predict whether a given shot would go in. The models I used were the following:
Logistic Regression
Random Forest
Gradient Boosting
AdaBoost
XGBoost
Neural Network

For each model, I used cross-validation to narrow down my feature set, including only the most relevant ones -- especially one that do not exhibit any collinearity with other feature. The feature set, hence, is narrowed down from 35 to just 6:
Shot Distance
Zone FG%
Defensive Win Shares per 48 Minutes
Defender Distance
Touch Time
Shot Clock Remaining
