# Reddit, Random Forests, and Vader

### Description

As a habitual reddit user for better or worse. I decided try and scrape reddit using BS4 and the reddit python api PRAW to see if I could build a classifier to predict the number of comments (interaction) a post has.

* The beginning of the notebook describes my methods of gathering Data. 
* The middle consists of:
	- feature engineering
	- bag of words with post titles
	- sentiment analysis with a nifty tool called VaderSentimentAnalyzer
* The final third consists of model comparison with Random Forest and Naive Bayes