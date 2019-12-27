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
brevity.

2-The second data set, Canadian_elections_2019.csv, contains a list of tweets regarding the 2019
Canadian elections. 

### The project has been implemented in the following steps to understand the datasets and and build the suitable models for getting the meaningful outcome-

### Data Cleaning-
The tweets, as given, are not in a form amenable to analysis -- there is too much ‘noise’.
Therefore, the first step is to “clean” the data.  A procedure is designed that prepares the
Twitter data for analysis by satisfying the requirements below.

o All html tags and attributes (i.e., /<[^>]+>/) are removed.
o Html character codes (i.e., &...;) are replaced with an ASCII equivalent.
o All URLs are removed.
o All characters in the text are in lowercase.
o All stop words are removed. Be clear in what you consider as a stop word.
o If a tweet is empty after pre-processing, it should be preserved as such




