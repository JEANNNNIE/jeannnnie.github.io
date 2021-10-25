---
title: "Classifying Documents with Large-texts Based on RNN&BERT"
categories:
  - computer techniques
tags:
  - machine learning 
  - deep learning
  - python
---
+ Collected a Chinese corpus bigger than 5G, composing of news, poems(shi), Chinese ci, classical proses, papers  
+ Implemented machine learning algorithms including Naive Bayers and Logistic regression to classify
+ Used word2vec, combined with TextCNN, TextRNN, TextRNN_Att, TextRCNN, DPCNN, Transformer with pytorch; compared the accuracies
+ Implemented ERNIE, bert, bert_cnn, bert_dpcnn, bert_rnn, bert_rcnn with pytorch; compare the accuracies

## Machine learning algorithms
![avatar](/assets/images/texts_classification/1.png){:width="450px"}![avatar](/assets/images/texts_classification/2.png){:width="450px"}  

## RNN & CNN
+ Models comparison
  
  | Model | Accuracy | 
  | ---- | ---- | 
  | TextCNN | 0.8734 | 
  | TextRNN | 0.8853 |  
  | TextRNN_Att | 0.8859 |  
  | **TextRCNN** | **0.8862** |  
  | DPCNN | 0.8853 |  
  | Transformer | 0.8752 |  
+ The best moder performance  
![avatar](/assets/images/texts_classification/3.png){:width="500px"}    
+ Confusion matrix  
![avatar](/assets/images/texts_classification/4.png){:width="600px"}  
  
## Bert & ERNIE
+ Models comparison
  
  | Model | Accuracy |
  | --- | --- |
  | ERNIE | 0.8869 |
  | **Bert** | **0.8890** |
  | Bert_cnn | 0.8819 |
  | Bert_dpcnn | 0.8777 |
  | Bert_rnn | 0.8809 |
  | Bert_rcnn | 0.8789 |
+ The best moder performance  
![avatar](/assets/images/texts_classification/5.png){:width="500px"}    
+ Confusion matrix  
![avatar](/assets/images/texts_classification/6.png){:width="600px"}  