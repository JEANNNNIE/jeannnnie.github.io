---
title: "Using C Language to Develop the Large-text Sets Search Engine"
categories:
  - computer techniques
tags:
  - C language
  - application development
---
(pic 0)
The search engine can quickly traverse a large number of documents, and quickly return documents that meet the conditions according to query terms and search patterns, and support sorting documents based on total number/number of keywords.

## query terms input mode
+ manual  
  ![avatar](../assets/images/c_search_engine/1.png)
+ script  
  realize bulk search  
  (pic 2)  
  ![avatar](../assets/images/c_search_engine/3.png)
  
## search mode
+ default search  
  return documents contain at least one query term
+ exact search  
  return documents contain all the query terms  
  ![avatar](../assets/images/c_search_engine/4.png)  
  ![avatar](../assets/images/c_search_engine/5.png)
  
## results sorts mode
+ top search  
  return the document contains most query terms  
  ![avatar](../assets/images/c_search_engine/6.png)  
  ![avatar](../assets/images/c_search_engine/7.png)  
  ![avatar](../assets/images/c_search_engine/8.png)  
  ![avatar](../assets/images/c_search_engine/9.png)  
+ top k search  
  return documents sorted in reverse order by the number of query terms contained  
  ![avatar](../assets/images/c_search_engine/10.png)  
  ![avatar](../assets/images/c_search_engine/11.png)  
  ![avatar](../assets/images/c_search_engine/12.png)  
  ![avatar](../assets/images/c_search_engine/13.png)  