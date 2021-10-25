---
title: "Part-Of-Speech Tagging for News Corpus Based on Deep Learning"
categories:
  - computer techniques
tags:
  - deep learning
  - python
---
Used Keras to implement POS tagging on Chinese news corpus  
Compare different models, and explored different skills to improve model performance

## Base model structure
![avatar](/assets/images/news_POS_tagging/1.png){:width="450px"}  

## Models comparison
| Model/strategy | Accuracy on test sets (descending order) |
| --- | --- |
| Bert | 0.9915 |
| Bi-LSTM with attention | 0.9878 |
| Bi-LSTM | 0.9867 |
| LSTM (Linear learning rate) | 0.9808 |
| LSTM (Step learning rate) | 0.9804 |
| LSTM | 0.9799 |
| RNN | 0.9787 |
| GRU | 0.9773 |

## Confusion matrix
![avatar](/assets/images/news_POS_tagging/2.png){:width="700px"}  

## Functional interface
![avatar](/assets/images/news_POS_tagging/3.png){:width="700px"}  