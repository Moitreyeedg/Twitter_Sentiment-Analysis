# Twitter_Sentiment-Analysis
I have picked up a very recent and controversial social issue in India created by a movie “Padmavat” - Initially name “Padmavati”. The movie created an immense controversy related to nation’s historical character “Padmavati”, a legendary Rajput Queen from Western region of India.
"Tweet_padmavat.csv" has all the data required for this challenge. we scrapped using query serch '#Padmavat" using Twitter' Official API. This has a limitation that more than week's old tweet can't be extracted.
Therefore, we have scrapped a thousand tweets for the prototype model while working on the big data set already scrapped using Python and saved as Tweet.csv for later use.

# Files 
1. credentials.txt holds :
  CONSUMER_KEY, CONSUMER_SECRET, ACCESS_TOKEN, ACCESS_SECRET
  
2. "Tweet_padmavat.csv" holds all the data we scrapped.
3. Tweet.csv (4.5 MB), more than 20k tweets from july,2017 till date.
4. "time_series_retweet.png:" Time Series Analysis for #retweet
5. "time_series_retweetvslikes" : Time Series Analysis of #retweet vs. Likes

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
4. Geolocation and interactive maps to identify regional inclination of positive or negative sentiments.
