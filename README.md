# Beyonce's  Renaissance Album


### A  Twitter Sentiment Analysis Project using Python and PowerBI. Click [here](https://medium.com/@Nonso_Analytics/beyonces-renaissance-album-a-twitter-sentiment-analysis-dec0e431337d) for the full article.

### By Chinonso OKONKWO

This Project was done using Natural Language Processing (NLP) Techniques. On the 29th of July, The Renaissance Album was released by Beyonce. The album dominated the twitter trends and spaces across different locations. As one of the most influential artist of her time, I thought it would be nice to see how the album fared generally on Twitter, Which Music Track fans loved the most, what time of the day they tweeted the most and generally Listeners/Tweeters Sentiments. I employed different python Libraries such as;

- Pandas - for Data Cleaning/Manipulation
- Tweepy - for Tweets Gathering
- NLTK - Natural Language Toolkit
- TextBlob - for Sentiment Analysis
- re - provides a set of powerful regular expression facilities, which allows one to quickly check whether a given string matches a given pattern (using the match function), or contains such a pattern (using the search function).
- MatPlotlib & WordCloud - for Data Visualization
- Emot - for Emojis identification

## Project Methodology

The main steps for this project can be summarized as follows:
<br>
- Introduction
- Data Gathering
- Data Assessment
- Data Cleaning
- Data Preprocessing
- Sentiment Analysis
- Explanatory Analysis/ Data Visualization
- Power BI Dashboard

## Results

### Sentiments Analysis

To analyze sentiments, I employed the use of TextBlob. Text blob is a python library for processing textual data. In sentiment analysis, it analyses each tweet by giving a Subjectivity and Polarity Score. Polarity scores, is then used to define a tweet as Positive or Neutral. In this analysis, A polarity score < 0, is Negative, while 0 or > 0 is Positive.
Find below, The distribution of Twitter User's Sentiment.

![download-2.png](attachment:download-2.png)

### Ranking of Tracks

The Ranking of the 16 tracks in Beyonce's Renaissance Album is shown below.

![download-2.png](attachment:download-2.png)

### Word Cloud of Processed Tweets

The Word Cloud shown below shows the most common words used. The frequently appearing words appears in a larger font size, and the words with the lest frequency a smaller font size.<br>
Also, the Renaissance Album cover is associated with an Horse and a Rider.
I tried to depict that with the word cloud.

![download-2.png](attachment:download-2.png)

## Remarks

Insights and Conclusion gotten from my Analysis

**Sentiment Analysis :** Within the timeframe of this Analysis, the positive sentiment score of 86.5% shows that the Album was well received among Twitter Users

**Popular Tracks:** Church Girl and Alien Superstar were the most talked about tracks (songs) on the Albums. It won't be surprising to see these songs top Musical Charts  during the timefarme of the Analysis as they've become fan favorites.

**Word Cloud** : The most common word used is Beyonce. This is attributed to the fact that she is the Owner of the Album, and of course any conversation related to the album is sure to likely include her name.
