# Overview 
The goal of this project was to build a spam-classification model for email clients. This was an end-of-chapter exercise from Chapter 3 of the book Hands-On Machine Learning (Aurelien), which covered classification tasks. 

Beyond the spam application specifically, this project was an opportunity to implement an end-to-end ML project while utilizing various methods to build and compare different classification models (performance metrics, hyperparameter tuning, ROC AUC curves, etc.).

# Methodology
## Bag-of-Words (BoW) 
I used a Bag-of-Words approach to create a feature vector that the models used for training. Essentially, this involves creating a vocabulary of the most common words found throughout all emails in the corpus ([Apache SpamAssassin](https://spamassassin.apache.org/old/publiccorpus/)). Then, for each email, we count how many instances of each word there are. 

<img src="figures/bow.jpeg" alt="BoW diagram" width="500">  

## Performance metrics
talk about precision 
talk about grid search for hyperparameter runing 
show picture of model precisions compared 

# Results
Include final performance metrics for Logistic Regression model 
Show picture of ROC AUC curves 

