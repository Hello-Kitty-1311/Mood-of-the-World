# Mood of the World - Tweet Sentiment Analysis

so this is my sentiment analysis project i've been working on and its supposed to like, figure out the mood of the world based on tweets. its a bit ambitious maybe but i had fun doing it.

## Why i made this ipynb

* i was curious about measuring "mood of teh world" instead of relying on pundit opinions.
* i wanted to see peoples real feelings, not just what news people say.
* i thought it would be cool to get a "world mood temperature".
* i wanted to get experience with big data visualization.


## How i made it

*  backend is in python (good for data stuff).
*   tweepy is used to grab tweets.
*   textblob does the sentiment analysis (its not perfect but pretty good).
*   regular expressions are used to clean tweets (remove urls, usernames, etc.).
*   pandas dataframes store the data.
*   plotly makes interactive graphs (pie charts, heatmaps, bar charts, time series).
*   KMeans clustering is for grouping similar sentiment tweets.
*   TF-IDF and CountVectorizer are there for text analysis, word clouds and finding frequency

## Struggles and what i have learned

*  getting twitter api to work was tough rate limits man! (learned about api limits tho).
*   making sense of data is hard!
*   getting perfect sentiment analysis is really tricky (sarcasm, slang, etc.).
*   generated sample data with time-based moods (weekends happier, morning grumps etc)
*   rate limit inturrupted data collection so graph may not displaying data coreectly
*   time series trends are visualised
*   getting graphs to work in colab took some fiddling.
*   learned a ton about data analysis, apis, and web dev.
*   definitely want to keep working on it and make it better in the upcoming commit

## usage of AI

* Error Lens : finds error in realtime
* Amazon Q Cli : real time code suggestion and explains error
* ChatGPT and Claude : solves bigger porblems