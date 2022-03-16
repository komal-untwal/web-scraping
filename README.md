# web-scraping
Twitter Data Scraping to identify the sentiments of stressful tweets on Twitter during the COVID-19 pandemic.

•One of the Major applications of Web scraping is Social media sentiment analysis. It is the use of natural language processing to monitor social discussions online and determine deeper context as it relates to a topic, brand, or theme.

•According to a survey, around 6,000 tweets are sent per second, equating to roughly 350,000 tweets every minute and 500 million tweets each day. Because Tweets are a realistic depiction of today's natural language on social media, Twitter is an ideal way to obtain data for your projects.

• My Project’s objective deals with application of social media sentiment analysis on twitter data to identify & address the mental or health related issues that people are facing due to & during the course of COVID-19 pandemic by scraping & analysing stressful tweets.

 The new Coronavirus outbreak has claimed many lives over the last three years and has been categorized as a pandemic. During this pandemic, there has been a significant rise in the average time spent by users on social media. People's mental health problems have also increased as a result of the pandemic, with '4 in 10 individuals in the United States experiencing depression and anxiety.' As a result of the increased use of social media and the rise in mental health disorders, particularly those related to stress, the project aims to forecast and detect the emotions and attitudes expressed in new tweets about stress.
 
 Data Scrapping:
• I've Scraped twitter data using the snscrape library.
• Sampling of data between a timeframe of November 2019 –  October 2021.
• Keyword used for this project is 'stress' for the retrieval of data.
• From my search I was able to gather a total of 30000 tweets with 11 columns.

Data Preprocessing:
1. Data cleaning.
2. Tokenization.
3. POS Tagging.
4. Stop words removal.
5. Lemmatization.

Sentiment Analysis:
I Used TextBlob, a python library to perform sentiment Analysis of our acquired data. TextBlob is a package for text processing, which offers a unified API for typical natural language processing (NLP) operations including part-of-speech tagging, noun phraseextraction, sentiment analysis, and more.

The following are the two metrics that are used to assess sentiment:

● Polarity: it refers to the degree to which a viewpoint is favorable or negative. The polarity scale runs from -1 to 1. (1 is more positive, 0 is neutral, -1 is more negative).
● Subjectivity: it refers to how subjective a person's opinion is. Subjectivity is measured on a scale of 0 to 1. (0 being very objective and 1 being very subjective).

Polarity & Subjectivity statistics plot:
![image](https://user-images.githubusercontent.com/72091290/158704609-fc7c8096-4fa6-4a9a-95fd-b2a6702d7969.png| width=100)
<img scr= "https://user-images.githubusercontent.com/72091290/158704609-fc7c8096-4fa6-4a9a-95fd-b2a6702d7969.png" width="200" height="400">

Sentiment Analysis bar plot:
![image](https://user-images.githubusercontent.com/72091290/158704712-faefe7b6-64ad-45e4-8b68-5d521255b534.png| width=100)


