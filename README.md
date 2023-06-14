# Sentiment Analysis on Twitter Data Regarding Nigeria 2023 Presidential Elections
![](elections.jpg)


This project aims to conduct exploratory analysis and sentiment analysis, utilizing the VADER Approach, on a  dataset extracted from Twitter API.

## Introduction

* ### **[Sentiment Analysis Using Twitter Data Regarding the 2023 Presidential Elections](https://github.com/ObaroJoseph/Data-Science-Projects/blob/main/Sentiment_Analysis_Nigeria_2023_Elections.ipynb)**

The 2023 presidential elections will exert a profound influence on the political landscape of Nigeria. The leading Presidential candidates are Peter Obi, Bola Tinubu and Atiku Abubakar. Accurately gauging public sentiment toward the political candidates is crucial for effectively measuring public opinion. In this project, a comprehensive analysis of Twitter data was undertaken to extract valuable insights and uncover hidden patterns that can provide political candidates with actionable knowledge that can significantly enhance their prospects of winning the election.


**_Disclaimer_**: _This project is exclusively intended to demonstrate my analytical skills and does not endorse any political affiliations or aspirations. Furthermore, utmost regard for the privacy of users has been observed_
.

## Problem Statement
1. What is the overall sentiment of Twitter users towards the political candidates?
2.  What significant trends and insights can be used by the political candidates?
3.  Who has the overall best impression on Twitter?
4.  What were the most associated positive and negative keywords associated with each presidential candidate?



## Skills Demonstrated 

This project involved the integration of various skills:
- Data collection
- Data Preprocessing
- Sentiment Analysis
- Natural Language Processing (NLP) techniques using Python Programming language, 
- Visualization
- Generation of meaningful interpretations and insights.

## About Data
A total collection of 150,000 tweets dating from January 31st and February 15th,2023  were obtained through the Twitter API using Python Open source library, snsscrape. These tweets were extracted by utilizing search queries corresponding to the official Twitter handles of the prominent presidential candidates, namely @PeterObi, @Atiku, and @OfficialAbat. For avoidance of bias, 50,000 tweets were mined from each handles. The data contains 11 columns and the description is given below. 

Variable Names  |  Description
:--------------:|:---------------------------------------------------:
Unnamed         | n/a
Date            | The date the tweet was created
Tweet URL       |  Unique URL or web address of a particular tweet
User            |  Twitter handle that made the tweet post
Source          |  Application or platform used in posting the tweets
Tweet           |  message or post that was shared
Like_counts     |  The number of times a particular tweet was liked
Retweet_count   |  The number of times a particular tweet was retweeted
Quote_count     |  The number of times a particular tweet was quoted
Reply_count     |  The number of times a particular tweet received replies


## Steps of the project

The steps of this project consists of the following sections:

1. Data Collection
2. Importing and Reading the datasets.
3. Data Exploration
4. Visualization
5. Feature Engineering
6. Text Preprocessing
7. Sentiment Analysis

## Summary of  Implmentation**

Data was extracted from Twitter API using the python library, snsscrape, and exploratory data analysis was  carried out on the data to identify hidden trends and patterns. The tweets will be pre-processed by removing irrelevant data to make it suitable for sentiment analysis.
Sentiment analysis task will be conducted on the pre-processed tweets utilising Natural Language Processing (NLP) libraries, VADER  to classify the tweets as positive, negative, or neutral. The results will be presented through charts and Word clouds to facilitate comprehension and communication of the findings.

The file, 

## Results and Visualization


- **Peter Obi**

 ![](Polarity_distribution_peter_obi.png)
 
 
 
 Positive Sentiment Word Cloud             |    Negative Sentiment Word Cloud
:-----------------------------------------:|:----------------------------------------------: 
   ![](positive_word_cloud_Peter_Obi.png)  |   ![](negative_word_cloud_Peter_Obi.png)             



- **Bola Tinubu**

![](Polarity_distribution_Bola_Tinubu.png)


 
 Positive Sentiment Word Cloud              |    Negative Sentiment Word Cloud
:------------------------------------------:|:----------------------------------------------: 
   ![](positive_word_cloud_Bola_Tinubu.png) |   ![](negative_word_cloud_Bola_Tinubu.png)             



- **Atiku Abubarkar**
![](Polarity_distribution_Atiku_Abubakar)


 Positive Sentiment Word Cloud                 |    Negative Sentiment Word Cloud
:---------------------------------------------:|:----------------------------------------------: 
   ![](positive_word_cloud_Atiku_Abubakar.png) |   ![](negative_word_cloud_Atiku_Abubakar.png) 
   
   
   
   
   
   
   
   
   
   
   
   
   
   
   
   
   
   
   
   
   
   
   
   
   
   
   
   
   
   
   










