---
title: "Evaluation for Mainstream Media's Influence During the Epidemic"
categories:
  - data analysis
tags:
  - python
  - informatics
---
+ Built an indicator system to evaluate the influence of mainstream media including media's activity, spreading scale and ability to leading opinions
+ Scrawled all the COVID-19 related micro-blogs of 14 national and 18 endemic mainstream media in China from Sina Weibo
+ Used factor analysis, cluster analysis, sentiment analysis, similarity analysis comprehensively

## Evaluation system
<table>
   <tr>
      <td>1st Class Index</td>
      <td>2nd Class Index</td>
      <td>Explanation for 2nd Class Index</td>
   </tr>
   <tr>
      <td>Activity(A)</td>
      <td>Number of Micro-blogs(A1)</td>
      <td>Number of Micro-blogs until 2020/5/20</td>
   </tr>
   <tr>
      <td></td>
      <td>Subscription Number(A1)</td>
      <td>Number of Accounts Subscribed by the Medium's Weibo Account</td>
   </tr>
   <tr>
      <td></td>
      <td>Number of Micro-blogs related to COVID-19(A3)</td>
      <td>Number of Micro-blogs related to COVID-19 released from 2020/1/1 to 2020/4/8</td>
   </tr>
   <tr>
      <td>Spreading Scale(B)</td>
      <td>Follower Number(B1)</td>
      <td>Number of Users Following the Medium's Weibo Account</td>
   </tr>
   <tr>
      <td></td>
      <td>Average Number of Forward of COVID-19 Related Micro-blogs(B2)</td>
      <td>Average Number of Forward of COVID-19 Related Micro-blogs released from 2020/1/1 to 2020/4/8</td>
   </tr>
   <tr>
      <td></td>
      <td>Average Number of Comment of COVID-19 Related Micro-blogs(B3)</td>
      <td>Average Number of Comment of COVID-19 Related Micro-blogs released from 2020/1/1 to 2020/4/8</td>
   </tr>
   <tr>
      <td>Ability to Lead Opinions(C)</td>
      <td>Average Number of Like of COVID-19 Related Micro-blogs(C1)</td>
      <td>Average Number of Like of COVID-19 Related Micro-blogs released from 2020/1/1 to 2020/4/8</td>
   </tr>
   <tr>
      <td></td>
      <td>Tendency of Comments(C2)</td>
      <td>How Positive or Negative Comments are Corresponding to the Micro-blogs</td>
   </tr>
   <tr>
      <td></td>
      <td>Sentiment of Comments(C3)</td>
      <td>How Positive or Negative Comments are in aspect of Sentiment</td>
   </tr>
</table>

## Results of factor analysis
+ 14 national mainstream media  
<table>
   <tr>
      <td>Weibo Account</td>
      <td>Spreading Scale</td>
      <td></td>
      <td>Activity</td>
      <td></td>
      <td>Ability to Lead Opinion</td>
      <td></td>
      <td>Total Score</td>
      <td>Total Ranking</td>
      <td>Category</td>
   </tr>
   <tr>
      <td></td>
      <td>Score</td>
      <td>Ranking</td>
      <td>Score</td>
      <td>Ranking</td>
      <td>Score</td>
      <td>Ranking</td>
      <td></td>
      <td></td>
      <td></td>
   </tr>
   <tr>
      <td>People's Daily</td>
      <td>2.63985</td>
      <td>1</td>
      <td>0.35358</td>
      <td>5</td>
      <td>-0.17807</td>
      <td>9</td>
      <td>1.4085</td>
      <td>1</td>
      <td>1</td>
   </tr>
   <tr>
      <td>CCTV News</td>
      <td>1.66529</td>
      <td>2</td>
      <td>0.37156</td>
      <td>4</td>
      <td>-0.23655</td>
      <td>10</td>
      <td>0.90356</td>
      <td>2</td>
      <td>1</td>
   </tr>
   <tr>
      <td>Xinhua News Agency</td>
      <td>0.70686</td>
      <td>3</td>
      <td>-0.45073</td>
      <td>10</td>
      <td>0.90167</td>
      <td>2</td>
      <td>0.37904</td>
      <td>3</td>
      <td>2</td>
   </tr>
   <tr>
      <td>China Daily</td>
      <td>-0.27463</td>
      <td>5</td>
      <td>0.97538</td>
      <td>3</td>
      <td>0.39272</td>
      <td>4</td>
      <td>0.09747</td>
      <td>4</td>
      <td>2</td>
   </tr>
   <tr>
      <td>Global Times</td>
      <td>-0.67159</td>
      <td>12</td>
      <td>2.3913</td>
      <td>1</td>
      <td>-0.8614</td>
      <td>13</td>
      <td>0.02846</td>
      <td>5</td>
      <td>3</td>
   </tr>
   <tr>
      <td>Workers' Daily</td>
      <td>-0.48199</td>
      <td>11</td>
      <td>-0.45631</td>
      <td>11</td>
      <td>2.34509</td>
      <td>1</td>
      <td>-0.06684</td>
      <td>6</td>
      <td>4</td>
   </tr>
   <tr>
      <td>China Women's News</td>
      <td>-0.06884</td>
      <td>4</td>
      <td>-0.72693</td>
      <td>12</td>
      <td>-0.00652</td>
      <td>6</td>
      <td>-0.1803</td>
      <td>7</td>
      <td>2</td>
   </tr>
   <tr>
      <td>Guangming Daily</td>
      <td>-0.40155</td>
      <td>9</td>
      <td>-0.14957</td>
      <td>7</td>
      <td>0.19025</td>
      <td>5</td>
      <td>-0.21433</td>
      <td>8</td>
      <td>2</td>
   </tr>
   <tr>
      <td>China News Service</td>
      <td>-0.85945</td>
      <td>14</td>
      <td>1.10844</td>
      <td>2</td>
      <td>-0.03356</td>
      <td>8</td>
      <td>-0.22662</td>
      <td>9</td>
      <td>2</td>
   </tr>
   <tr>
      <td>Legal Daily</td>
      <td>-0.40017</td>
      <td>8</td>
      <td>-0.8116</td>
      <td>13</td>
      <td>0.71019</td>
      <td>3</td>
      <td>-0.2846</td>
      <td>10</td>
      <td>2</td>
   </tr>
   <tr>
      <td>China National Radio</td>
      <td>-0.48147</td>
      <td>10</td>
      <td>-0.3774</td>
      <td>8</td>
      <td>-0.01529</td>
      <td>7</td>
      <td>-0.32445</td>
      <td>11</td>
      <td>2</td>
   </tr>
   <tr>
      <td>PLA Daily</td>
      <td>-0.39585</td>
      <td>7</td>
      <td>-0.39981</td>
      <td>9</td>
      <td>-0.55679</td>
      <td>12</td>
      <td>-0.34757</td>
      <td>12</td>
      <td>2</td>
   </tr>
   <tr>
      <td>Science and Technology Daily</td>
      <td>-0.67474</td>
      <td>13</td>
      <td>-0.12501</td>
      <td>6</td>
      <td>-0.50862</td>
      <td>11</td>
      <td>-0.43109</td>
      <td>13</td>
      <td>2</td>
   </tr>
   <tr>
      <td>Farmers' Daily</td>
      <td>-0.30173</td>
      <td>6</td>
      <td>-1.7029</td>
      <td>14</td>
      <td>-2.14312</td>
      <td>14</td>
      <td>-0.74125</td>
      <td>14</td>
      <td>5</td>
   </tr>
</table>

+ 18 endemic mainstream media
<table>
   <tr>
      <td>Weibo Account</td>
      <td>Spreading Scale</td>
      <td></td>
      <td>Ability to Lead Opinion</td>
      <td></td>
      <td>Activity</td>
      <td></td>
      <td>Total Score</td>
      <td>Total Ranking</td>
      <td>Category</td>
   </tr>
   <tr>
      <td></td>
      <td>Score</td>
      <td>Ranking</td>
      <td>Score</td>
      <td>Ranking</td>
      <td>Score</td>
      <td>Ranking</td>
      <td></td>
      <td></td>
      <td></td>
   </tr>
   <tr>
      <td>The Beijing News</td>
      <td>3.13177</td>
      <td>1</td>
      <td>-0.37429</td>
      <td>12</td>
      <td>0.16771</td>
      <td>9</td>
      <td>1.34250 </td>
      <td>1</td>
      <td>1</td>
   </tr>
   <tr>
      <td>The Paper</td>
      <td>2.04966</td>
      <td>2</td>
      <td>0.11431</td>
      <td>9</td>
      <td>-1.16524</td>
      <td>16</td>
      <td>0.77727 </td>
      <td>2</td>
      <td>1</td>
   </tr>
   <tr>
      <td>Yunna Daily</td>
      <td>-0.30265</td>
      <td>10</td>
      <td>3.10574</td>
      <td>1</td>
      <td>0.99106</td>
      <td>4</td>
      <td>0.67662 </td>
      <td>3</td>
      <td>2</td>
   </tr>
   <tr>
      <td>Changjiang Daily</td>
      <td>0.09690</td>
      <td>4</td>
      <td>0.91462</td>
      <td>2</td>
      <td>0.81851</td>
      <td>5</td>
      <td>0.35643 </td>
      <td>4</td>
      <td>3</td>
   </tr>
   <tr>
      <td>Yangtse Evening Post</td>
      <td>0.12997</td>
      <td>3</td>
      <td>0.19140</td>
      <td>6</td>
      <td>1.04884</td>
      <td>3</td>
      <td>0.24695 </td>
      <td>5</td>
      <td>3</td>
   </tr>
   <tr>
      <td>Tonight News Paper</td>
      <td>0.01094</td>
      <td>7</td>
      <td>-0.79892</td>
      <td>17</td>
      <td>1.30776</td>
      <td>2</td>
      <td>0.01564 </td>
      <td>6</td>
      <td>3</td>
   </tr>
   <tr>
      <td>Beijing Daily</td>
      <td>0.01198</td>
      <td>5</td>
      <td>0.44143</td>
      <td>4</td>
      <td>-0.73022</td>
      <td>14</td>
      <td>-0.00166 </td>
      <td>7</td>
      <td>3</td>
   </tr>
   <tr>
      <td>Yangcheng Evening News</td>
      <td>-0.20903</td>
      <td>8</td>
      <td>0.16511</td>
      <td>8</td>
      <td>0.27980</td>
      <td>8</td>
      <td>-0.01836 </td>
      <td>8</td>
      <td>3</td>
   </tr>
   <tr>
      <td>Qilu Evening News</td>
      <td>0.01190</td>
      <td>6</td>
      <td>-0.47456</td>
      <td>13</td>
      <td>0.48400</td>
      <td>6</td>
      <td>-0.02944 </td>
      <td>9</td>
      <td>3</td>
   </tr>
   <tr>
      <td>Shaanxi News Network</td>
      <td>-0.50603</td>
      <td>11</td>
      <td>-0.72273</td>
      <td>16</td>
      <td>1.72624</td>
      <td>1</td>
      <td>-0.14015 </td>
      <td>10</td>
      <td>3</td>
   </tr>
   <tr>
      <td>Qianlong Network</td>
      <td>-0.26104</td>
      <td>9</td>
      <td>-0.31173</td>
      <td>11</td>
      <td>-0.10898</td>
      <td>11</td>
      <td>-0.19952 </td>
      <td>11</td>
      <td>3</td>
   </tr>
   <tr>
      <td>Hangzhou Network</td>
      <td>-0.64901</td>
      <td>17</td>
      <td>0.17564</td>
      <td>7</td>
      <td>-0.31777</td>
      <td>12</td>
      <td>-0.29674 </td>
      <td>12</td>
      <td>3</td>
   </tr>
   <tr>
      <td>Cnhubei Network</td>
      <td>-0.60249</td>
      <td>16</td>
      <td>0.44531</td>
      <td>3</td>
      <td>-0.91846</td>
      <td>15</td>
      <td>-0.30196 </td>
      <td>13</td>
      <td>3</td>
   </tr>
   <tr>
      <td>Public Network</td>
      <td>-0.54951</td>
      <td>13</td>
      <td>-0.10923</td>
      <td>10</td>
      <td>-0.60530</td>
      <td>13</td>
      <td>-0.35437 </td>
      <td>14</td>
      <td>3</td>
   </tr>
   <tr>
      <td>Zhengzhou Evening News</td>
      <td>-0.56280</td>
      <td>14</td>
      <td>-0.64191</td>
      <td>15</td>
      <td>-0.03773</td>
      <td>10</td>
      <td>-0.39592 </td>
      <td>15</td>
      <td>3</td>
   </tr>
   <tr>
      <td>Dongfang Network</td>
      <td>-0.51428</td>
      <td>12</td>
      <td>0.35795</td>
      <td>5</td>
      <td>-2.11950</td>
      <td>18</td>
      <td>-0.45023 </td>
      <td>16</td>
      <td>4</td>
   </tr>
   <tr>
      <td>Wuhan Evening News</td>
      <td>-0.57238</td>
      <td>15</td>
      <td>-1.85998</td>
      <td>18</td>
      <td>0.35537</td>
      <td>7</td>
      <td>-0.60877 </td>
      <td>17</td>
      <td>5</td>
   </tr>
   <tr>
      <td>Fujian Daily</td>
      <td>-0.71392</td>
      <td>18</td>
      <td>-0.61816</td>
      <td>14</td>
      <td>-1.17608</td>
      <td>17</td>
      <td>-0.61830 </td>
      <td>18</td>
      <td>3</td>
   </tr>
</table>

## Results of cluster analysis
+ 14 national mainstream media  
![avatar](/assets/images/mainstream_media_influence/1.png){:width="700px"}  

+ 18 endemic mainstream media  
![avatar](/assets/images/mainstream_media_influence/1.png){:width="700px"}  