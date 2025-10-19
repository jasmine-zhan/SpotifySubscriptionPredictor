# SpotifySubscriptionPredictor

# Tools:
Python, Pandas, Scikit-learn, Matplotlib, Seaborn

# Goal: 
This project predicts which Spotify users on free plans are most likely to upgrade to a premium subscription and which premium plan they’d choose (Individual, Family, or Student). The analysis supports Spotify’s marketing efforts by identifying potential subscribers and optimizing promotional strategies

# Overview:
Analyzed a Kaggle dataset of 520 users containing behavioral and satisfaction metrics to predict subscription intent.

# Key objectives included:
- Binary classification: Predicting whether a free user would upgrade to Premium.
- Multiclass classification: Predicting the specific Premium plan (Individual, Family, or Student).

# Methods:
- Data Preparation: Cleaned categorical variables using one-hot encoding and mapped plan prices.
- Modeling: Trained Logistic Regression, ADABoost, and Gradient Boosting for binary classification; and Multi-class Logistic Regression, Decision Tree, Bagging, and Random - Forest for multiclass prediction.
Evaluation: Assessed model performance using F1-score to account for class imbalance.

# Results:
- ADABoost achieved the highest performance in predicting upgrade likelihood.
- Multi-class Logistic Regression delivered the most reliable results for predicting plan type.
- A marketing simulation offering one free month of Premium to the top 2% predicted subscribers generated an estimated $153 revenue increase over three months.


[Colab Link (may be able to see output)](https://colab.research.google.com/drive/1vl4UnqVehcZxhV3SYcQLTe6Jk5oBg7Ik?usp=sharing)

[Presentation](https://docs.google.com/presentation/d/1XqjkieSEsCI2y07yiFuCBD-TnA95X7BwhwHq7zTCBV0/edit?usp=sharing)
