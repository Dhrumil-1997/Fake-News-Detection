# Fake-News-Detection

## About

 made-up tale with the goal to deceive or mislead is defined as fake news. In this work, we
use NLP models to solve the problem of detecting fake news. The exponential spread of fake
news creates an urgent demand for automated
labelling and detection of such distorted material. Automated identification of fake news,
on the other hand, is a difficult problem since it
necessitates the model’s understanding of natural language subtleties. Furthermore, the vast
majority of existing fake news detection algorithms approach the problem as a binary classification job, limiting the model’s capacity to
grasp how connected or unrelated the reported
news is to the genuine news. To fill these shortcomings, we offer a neural network architecture that can accurately predict the attitude of a
given news is fake or reliable. With our model
architecture, we are able to achieve accuracy
above 90% on test data.

## Evaluation Models

1. Multinomial Na¨ıve Bayes
2. Passive Aggressive Algorithm
3. Logistic Regression
4. Recurrent Neural Network (RNN)
5. Long Short-Term Memory (LSTM)

## Dataset

In this project, the dataset is being taken from
Kaggle’s Fake news Detection challenge. The
dataset contains the following files: train.csv for
training purpose, test.csv for testing purpose, and
submit.csv to validate. The train dataset contains
five columns :- id, title, author, text and label, while
test.csv has four columns :- id, title, author, text and
lastly submit.csv has two columns :- id, label. The
size of dataset for train.csv, test.csv and submit.csv
are 20800*5, 5200*4 and 5200*2 respectively. We
have almost 12000 Reliable(0) and 10000 Fake(1)
data after removing all NULL values.

## Result

![alt text](https://github.com/Dhrumil-1997/Fake-News-Detection/blob/main/Screenshot%202023-03-15%20214514.png)

