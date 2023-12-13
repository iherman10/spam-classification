# Overview 
The goal of this project was to build a spam-classification model for email clients. This was an end-of-chapter exercise from Chapter 3 of the book Hands-On Machine Learning (Aurelien), which covered classification tasks. 

Beyond the spam application specifically, this project was an opportunity to implement an end-to-end ML project while utilizing various methods to build and compare different classification models (performance metrics, hyperparameter tuning, ROC AUC curves, etc.).

# Methodology
## Bag-of-Words (BoW) 
I used a Bag-of-Words approach to create a feature vector that the models used for training. Essentially, this involves creating a vocabulary of the most common words found in all emails belonging to the corpus ([Apache SpamAssassin](https://spamassassin.apache.org/old/publiccorpus/)).

# Results