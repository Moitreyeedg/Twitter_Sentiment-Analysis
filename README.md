# Twitter_Sentiment-Analysis
I have picked up a very recent and controversial social issue in India created by a movie “Padmavat” - Initially name “Padmavati”. The movie created an immense controversy related to nation’s historical character “Padmavati”, a legendary Rajput Queen from Western region of India.
"Tweet_padmavat.csv" has all the data required for this challenge. we scrapped using query serch '#Padmavat" using Twitter' Official API. This has a limitation that more than week's old tweet can't be extracted.
Therefore, we have scrapped a thousand tweets for the prototype model while working on the big data set already scrapped using Python and saved as Tweet.csv for later use.

# Please Note that I have shared here the initial code for Data Scrapping from Twitter, Data Cleaning, Data Visialisation, Time Series Analysis of Twitter Data and Sentiment Analysis using Text Blob. For further code of Model training, tuning and test validation, please drop an email @ moitreyee77@gmail.com with subject line "Sentiment analysis Code Request".

# Objectives-
Our objective is to -
1.	Categorising Tweeter text to Positive/Negative/Neutral sentiment and categorising words to find out the cause behind the negative sentiments.
2.	A Demographic information from other social media/available Dataset would be added to generate the insight of demographic influence (if any).
3.	Analysing extensively with multiple classification models like Gaussian Naïve Bayes, Decision Tree, logistics regression etc. to understand and use the best suitable one.
4.	Measure the model accuracy with confusion matrix and cross validation.
5.	Provide a time series analysis to generate the insight about how Sentiment changes over a period of time.
6.	Create Word cloud and geo-interactive maps to provide great visualization. 


# Files 
1. credentials.txt holds :
  CONSUMER_KEY, CONSUMER_SECRET, ACCESS_TOKEN, ACCESS_SECRET (Credentials are supposed to kept, therefore this file is not uploaded here)
  
2. "Tweet_padmavat.csv" holds all the data we scrapped.
3. Tweet.csv (4.5 MB), more than 20k tweets from july,2017 till date, I have done data cleaning, stop word processing and sentiment classification on this file.
4. "time_series_retweet.png:" Time Series Analysis for #retweet
5. "time_series_retweetvslikes" : Time Series Analysis of #retweet vs. Likes
6.

# Analysis Plan

1. Distribution and Metrics
2. Data Cleaning, Data Munging and data Wrangling (Clustering text data according to their
main message)
3. Visualization
4. Feature Selection
5. Cross-Validation and Prediction Model testing
6. Test model to predict given a tweet can it be analyzed to predict it's sentiment correctly

# Deliverables
We would like to generate some insights from these tweets.
 1. Sentiment expressed in each tweet (there would be some tweets that don't express a
sentiment or not applicable). The sentiment Positive/Negative/Neutral/NA will be provided against the tweet. 
2. Categorized words from the tweets. 
3. Details of algorithm used. 
4. Word Cloud.
5. Geolocation and interactive maps to identify regional inclination of positive or negative sentiments.
