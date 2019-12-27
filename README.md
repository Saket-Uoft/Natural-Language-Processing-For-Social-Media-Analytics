# Natural-Language-Processing-of-Tweets
## Project - Predicting the Outcome of Canadian Elections 2019 based upon Election Tweets

### Background
Sentiment analysis is a technology of increasing importance in the modern society as it allows
individuals and organizations to detect trends in public opinion by analyzing social media
content. Keeping abreast of socio-political developments is especially important during periods
of policy shifts such as election years, when both electoral candidates and companies can benefit
from sentiment analysis by making appropriate changes to their campaigning and business
strategies respectively.

The purpose of this Project is to compute the sentiment of text information - in our case,
tweets posted in 2019 Canadian elections - and answer the research question: “What can public
opinion on Twitter tell us about the Canadian political landscape in 2019?” The goal is to
essentially use sentiment analysis on Twitter data to get insight into the 2019 Canadian elections.

### Datasets
1- Two sets of data are used for this assignment. The generic_tweets.txt file contains tweets that
have had their sentiments already analyzed and recorded as binary values 0 (negative) and 4
(positive). Each line is a single tweet, which may contain multiple sentences despite their
brevity. The comma-separated fields of each line are:

0 class the polarity of each tweet (0 = negative emotion, 4 = positive emotion)
1 id the id of the tweet (e.g. 2087)
2 date the date of the tweet (e.g. Sat May 16 23:58:44 UTC 2009)
3 query the query (e.g. lyx). If there is no query, then this value is NO_QUERY.
4 user the user that tweeted (e.g. robotickilldozr)
5 text the text of the tweet (e.g. Lyx is cool)

2-The second data set, Canadian_elections_2019.csv, contains a list of tweets regarding the 2019
Canadian elections. The fields of each line are:
0 sentiment can be “positive” or “negative”
1 negative_reason reason for negative tweets. Left blank for positive tweets.
2 text the text of the tweet


