# ![](https://ga-dash.s3.amazonaws.com/production/assets/logo-9f88ae6c9c3871690e33280fcf557f33.png) Project 3: Streaming Platform (Netflix vs Disney plus)

### Problem Statement
Using Reddit posts we intend to perform sentiment analysis to understand and compare user attitudes towards Netflix and Disney+ Hotstar. This will reveal how positively or negatively users discuss each streaming platform. Moreover, we aim to build a model to predict whether a streaming-related post is discussing Netflix or Disney+. This will help understand which streaming service is being referenced and which manner they are mentioned in social media conversations.


### Methodology
For project 3, goal is two-fold:
1. Using Reddit's API, we collect posts from two subreddits
- Disney plus : https://www.reddit.com/r/DisneyPlus/
- Netflix : https://www.reddit.com/r/netflix/

2. Using NLP to train classifiers (binary classification problem) on which a given post came from.


### Executive Summary
Two classification models, Naïve Bayes and Logistic Regression, were used to predict Reddit posts into streaming platforms ‘Netflix’ or ‘Disney’. The metric used to evaluate the model is accuracy score, which both were above the baseline. The accuracy scores for Naïve Bayes are 70% and Logistic Regression 85%. The Logistic Regression model showed overfitting. Further hyperparameter tuning can help improve both model’s scores by using GridSearchCV. Sentiment analysis was performed on the title and body of the Reddit posts. However, both platforms showed similar results in terms of positive, neutral, and negative vocabulary. Netflix post titles showed a slightly negative sentiment. The conclusion is that Reddit audiences are more engaged with Disney due to the higher number of posts, perhaps due to Disney’s frequent news updates such as subscription price increases and Hulu integration.