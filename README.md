# 4G-COVID-19-challenge

***This project won the 2nd prize and the most valuable dataset prize in the UCD MSBA COVID-19 Challenge***

**Objectives**

This project aims to ensure people’s mental health in the COVID-19 pandemic by giving suggestions about what acitvities that people should take part in more and the ones that people should avoid. In details, we used NLP to understand the emotion pattern of people and identify factors causing people positive and negative emotions.

**Data Resource**

We use Twitter website as our data resource. We scraped the Tweets with the hashtage of #StayHome from March 5th to April 12th using the package called *GetOldTweets3*.

The package link is here: https://pypi.org/project/GetOldTweets3/

**Structure**

Web Scpraing
Exploratory Data Analysis
Text Preprocessing
Sentiment Analysis
Word Clouds
Topic Modeling
- Determining the optimal number of topics
- Finding key words for each topic using optimal LdaMallet model
- Finding the beneficial topics by combining sentiment analysis and topic modeling
- Finding the top 3 popular activities in different regions
- Finding the beneficial activities by combining sentiment analysis and single word analysis

**Recommendations**

Based on the topic analysis and single word analysis, we give the following suggestions to people who feel mental discomfort: 

First of all, these popular activities are proved to be very positive: listening to and singing songs, watch movies or TV series, virtually connecting with your family and fiends, reading and workout.

Besides, we also found several activities that are surprisingly very helpful to people's emotions:
First, help others, whether sharing free food or donating money works.
Second, saying a prayer does help you feel better
Third, ordering food online rather than cooking by yourself has a more positive effect on your emotion.
Last but not the least, stop playing games all day. It’s not as positive as you thought.

**Note**

Please put mallet-2.0.8 in the same folder with the code so that the code runs sucessfully.

**Next Steps**
- Adding emoji analysis to the text analysis
- Combining lasso and word-of-bag to do a single-word analysis
