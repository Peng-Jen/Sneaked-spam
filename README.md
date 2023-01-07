# Sneaked-spam
The final project for Introduction of Text-Mining in National Taiwan University.

## Abstract
We do some research about **How to make spams not to be detected**.  
At first, we train a model to classify whether the input data is a ham or a spam.  
Then we try to modify the content of spams and re-input to the trained model, checking whether the recall of spams is decreasing.

## Data source
From **kaggle**
- ham: 2,551
- spam: 500

## Model
- Multinomial Naive Bayes
- Bernoulli Naive Bayes
- tfidf to SVM
- SVD to SVM

## Method we've tried
- Delete the links in spams
- Delete the special symbols (ex: @, #, ...) in spams
- Using `w2v` to change some words in spams
- Delete some words in spams which are unseen in hams
- Append some words in hams which are unseen in spams to spams
