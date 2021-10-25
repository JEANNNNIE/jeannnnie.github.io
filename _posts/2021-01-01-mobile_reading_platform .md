---
title: "A Study on the Guidance of Charged Mobile Reading Platform Development"
categories:
  - data analysis
tags:
  - data visualization
---
A case study on [Jinjiang Literacy](https://www.jjwxc.net/)
was taken to explore the factors influencing the subscription of an online literary work.

## Data crawling
We used Python to crawl data from [there](https://www.jjwxc.net/bookbase_slave.php?t=0&booktype=&opt=&page=1&endstr=true&orderstr=4).
+ Work attributions  
We crawled data of 6378 literary works.  
![avatar](/assets/images/mobile_reading_platform/1.png){:width="700px"}  
+ Chapter payment  
We crawled nearly 900 thousand payment records.  
![avatar](/assets/images/mobile_reading_platform/2.png){:width="400px"}  
+ Comments   
We crawled more than 1.2 million comments.  
![avatar](/assets/images/mobile_reading_platform/3.png){:width="700px"}  
  
## Regression analysis
First, second and third order regression was performed using the Ridge, Lasso, LinearRegression, ElasticNet algorithm in Python.  
+ Results  
![avatar](/assets/images/mobile_reading_platform/4.png){:width="700px"}  
+ The best regression coefficient of each factor  
![avatar](/assets/images/mobile_reading_platform/5.png){:width="500px"}  
log 10  
![avatar](/assets/images/mobile_reading_platform/6.png){:width="500px"}  

## Cluster analysis