# Credit-Card-Fraud-Detection

## Introduction
In our modern world, most of money transactions have turned virtual. It has certainly eased the way we transfer funds and moreover, it is easy and fast. But then, the risk of frauds has substantially escalated. For the same reasons, it is essential to find solutions that bring more security to credit cards users. Also, with the sheer volume of credit card transactions done everyday, it has become necessary to automate this process rather than employing more individuals for parsing through each and every transaction.

## Overview
This project aims at detecting fraudulent transactions using anomaly detecion(Isolation Forest, Local Outlier Factor) and boosting algorithms(Light GBM).
It offers an insight on how outlier detection algorithms and boosted trees can help in this regard. 

## Dataset
This dataset(~77MB zip) can be downloaded from [here.](https://www.kaggle.com/mlg-ulb/creditcardfraud)

## Dependencies
* pip install tensorflow
* pip install keras
* pip install lightgbm

## Acknowlegdements
* [A Comparative Evaluation of Unsupervised Anomaly Detection Algorithms for Multivariate Data](https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0152173)
* [What is LightGBM, How to implement it? How to fine tune the parameters?](https://medium.com/@pushkarmandot/https-medium-com-pushkarmandot-what-is-lightgbm-how-to-implement-it-how-to-fine-tune-the-parameters-60347819b7fc)
