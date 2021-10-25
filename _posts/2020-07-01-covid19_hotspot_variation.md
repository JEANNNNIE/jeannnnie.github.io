---
title: "Analysis and network visualization of academic and social COVID-19 hotspot variations"
categories:
  - data analysis
tags:
  - data visualization
  - network analysis
---
+ Crawled COVID-19 related data from Web of Science (WOS) and Twitter
+ Used Gephi, VOSviwer, HistCite, Pajek and R to analyze and visualize network data, reflecting academic and social COVID-19 hotspot variations

## Academic hotspot
### Co-occurrence analysis of paper keywords
+ Visualization  
![avatar](/assets/images/covid19_hotspot_variation/1.png){:width="700px"}  
+ Community detection  

| Number | subresearch field | keyword representative | weights |
| --- | --- | --- | --- |
| 1 | Pathological studies | novel coronavirus, sars, hydroxychloroquine, chloroquine, respiratory failure | 18.72 |
| 2 | Clinical trials | tracheotomy, intensive care, pulmonary ultrasound, emergency medicine | 7.27 |
| 3 | Mental Health | Mental Health, Anxiety, Depression, Fear, lockdown, Crisis | 47.16 |
| 4 | Antiepidemic strategy | Prevention, isolation, public health emergencies, health policies | 7.63 |
| 5 | Predisposing factors | hypertension, diabetes, smoking, risk factors, elderly | 7.71 |
| 6 | Medical Education | Education, Technology, Online Education, E-Learning, Learning | 5.5 |
| 7 | Detection technology | CT examination, clinical characteristics, nucleic acid detection, chest X-ray | 9.76 |
| 8 | Social Studies | Climate change, geopolitics, economics, Environment, Globalization | 5.72 |
| 9 | Epidemiological | transmission, latency, mathematical modeling, mathematical model | 8.79 |
| 10 | Immune studies | antiviral substances, immunosuppression, immunomodulation, antibiotics | 8.87 |
| 11 | Social Informatics | Social Isolation, Twitter, Fake News, Data Science | 18.8 |
| 12 | Bioinformatics | Artificial Intelligence, Bioinformatics, machine learning, Network Pharmacology | 29.29 |
| 13 | Medical resources | personal protection equipment, medical personnel, masks, n95 | 7.86 |
| 14 | Social management | management, diversion | 7 |
| 15 | Telemedicine | hygiene, e-care, resource allocation | 10 |
| 16 | Infection symptoms | anorexia,  E. N. T. , olfactory dysfunction | 5.2 |

### Citation network analysis
+ Visualization  
![avatar](/assets/images/covid19_hotspot_variation/2.png){:width="700px"}  
+ Corresponding paper  

| 编号 | 文献名（译成中文） | 子领域 |
| --- | --- | --- |
| 1 | 澳门10名COVID-19患者临床标本及临床特征对SARS-CoV-2RNA脱落的评估 | 病理研究 |
| 2	| 在COVID-19疫情快速上升期间，中国居民对COVID-19的知识、态度和做法：快速在线横断面调查 | 社会研究 |
| 3	| COVID-19：关于新型冠状病毒的已经掌握和需要被掌握的知识 | 医疗教育 |
| 4	| 突破：氯奎宁磷酸盐在临床研究中在治疗COVID-19相关肺炎方面显示出明显的疗效 | 临床实验 |
| 5	| 九名孕妇COVID-19感染的临床特征和宫内垂直传播潜力：医学记录回顾回顾 | 易感因素 |
| 6	| 中国武汉COVID-19成人住院病人死亡临床历程及危险因素：回顾性队列研究 | 易感因素 |
| 7	| 与急性呼吸窘迫综合征有关的COVID-19的病理发现 | 病理研究 |
| 8	| 中国疾病预防控制中心报告72314例，其中冠状病毒病疫情的特点及重要教训 | 流行病学 |
| 9	| 2019年中国冠状病毒病临床特征 | 临床试验 |
| 10 | 基于对150例中国武汉患者数据的分析，COVID-19死亡率的临床预测 | 流行病学 |
| 11 | COVID-19对已有消化系统疾病患者的影响 | 易感因素 |
| 12 | 2019年冠状病毒病的潜伏期（COVID-19）来自公开报告的确诊病例：估计和应用 | 流行病学 |
| 13 | 洛皮纳维尔-里托纳韦在患有重症COVID-19的成人中试验 | 临床试验 |

## Social hotspot
### Co-occurrence analysis of words in tweets
+ Visualization  
![avatar](/assets/images/covid19_hotspot_variation/3.png){:width="700px"}  
+ Community detection  

| Number | subtopic | representative word | weight | 
| --- | --- | --- | --- |  
| 1 | Global epidemic situation | deaths, lockdown, impact, outbreak, pandemic  | 15.52 |
| 2 | Asia and Africa | Akan, Dali, Poland, Mandela and Ideology | 8.43 |
| 3 | The Moral Rule of Law and Management | Act, Human Nature, Legislation, Officials, Power, and Psychology | 7.16 |
| 4 | New deaths | millions, many, 30,100,10,21 … | 4.81 |
| 5 | Politics | Real Donald Trump, touting, Movement, Failure | 4.27 |
| 6 | Events affected by COVID-19 | 2020, the Olympic Games, Tokyo, blocked, postponed | 3.15 |
| 7 | social assistance | saves, gives support, and provides | 3.04 |
| 8 | Medical resources for epidemic prevention | masks, supply, medical treatment, community, n95, equipment | 2.57 |

### Time-sync dynamic network
+ Visualization  
![avatar](/assets/images/covid19_hotspot_variation/4.png "3.22"){:width="300px"}
![avatar](/assets/images/covid19_hotspot_variation/5.png "3.23-3.25"){:width="300px"}
![avatar](/assets/images/covid19_hotspot_variation/6.png "3.26-3.28"){:width="300px"}
![avatar](/assets/images/covid19_hotspot_variation/7.png "3.29-3.31"){:width="300px"}
![avatar](/assets/images/covid19_hotspot_variation/8.png "4.1-4.3"){:width="300px"}
![avatar](/assets/images/covid19_hotspot_variation/9.png "4.4-4.6"){:width="300px"}  
+ Corresponding words groups  
![avatar](/assets/images/covid19_hotspot_variation/10.png){:width="700px"}  