# e-commerce Reviews Sentiment Analysis

Dataset source: https://www.kaggle.com/farhan999/tokopedia-product-reviews

Simple Sentiment Analysis based on e-commerce reviews.
Sentiment was labeled regarding to rating score (0 - 5) given by the reviewers.
Score more than and equal to 3 are considered has Positive sentiment, otherwise has Negative sentiment.

XGBoost was trained using 10-fold cross validation with Randomized Search parameter tuning.

Model performance on Test Data:
![image](https://user-images.githubusercontent.com/70200533/147870749-d4e4bffa-8106-47f2-be5b-dcda74c0568a.png)
