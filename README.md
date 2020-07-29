# Sentimental analysis by using Natural language processing (NLP)
Sentiment analysis is the interpretation and classification of emotions (positive, negative and neutral) within text data using text analysis techniques.
Natural language processing (NLP) is the ability of a computer program to understand human language as it is spoken.

## Packages required:
(a) numpy 
(b) matplotlib
(c) pandas 
(d) re
(e) nltk 

## Description:
In this project we will build a model which will predict whether the reviews given in the restaurants by the customers is positive or not. For that we will build
"bag of words model" (In this model, a text is represented as the bag of its words, disregarding grammar and even word order but keeping multiplicity)

![s](https://user-images.githubusercontent.com/68856803/88803839-b0523d00-d1ca-11ea-98cf-b6a0093e559d.png)

## About the dataset:
-> Dataset is a 'tsv' file which consists of 1000 reviews (positive and negative). 

-> Each review is associated with a number 0 or 1. 

-> positive reviews are associated with number 1 and negative reviews are associated with number 0

## Steps to build this project:
(a) Import the required libraries

(b) Import the dataset

(c) Clean the texts by removing the unnecessary stopwords

(d) Create the Bag of Words model

(e) Split the dataset into the Training set and Test set

(f) Train the Naive Bayes model on the Training set

(g) Predict the Test set results

(h) Make the Confusion Matrix

## Outputs:
![a](https://user-images.githubusercontent.com/68856803/88807518-746da680-d1cf-11ea-9e6d-4d5ccc3a7295.png)

![b](https://user-images.githubusercontent.com/68856803/88807528-76d00080-d1cf-11ea-8aa1-082175ffaaf4.png)
