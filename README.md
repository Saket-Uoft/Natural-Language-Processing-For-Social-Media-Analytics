## Project - Predicting the Outcome of Canadian Elections 2019 using NLP Analytics

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

#### The project has been implemented in the following steps to understand the datasets and and build the suitable models for getting the meaningful outcome-

### 1-Data Cleaning-
The tweets, as given, are not in a form amenable to analysis -- there is too much ‘noise’.
Therefore, the first step is to “clean” the data.  A procedure is designed that prepares the
Twitter data for analysis by satisfying the requirements below.

o All html tags and attributes (i.e., /<[^>]+>/) are removed.

o Html character codes (i.e., &...;) are replaced with an ASCII equivalent.

o All URLs are removed.

o All characters in the text are in lowercase.

o All stop words are removed. Be clear in what you consider as a stop word.

o If a tweet is empty after pre-processing, it should be preserved as such

### 2-Exploratory analysis-

A simple procedure is designed  that determines the political party (Liberal, Conservative,
NDP, None) of a given tweet and applied this procedure to all the tweets in the 2019
Canadian elections dataset. Relevant keywords and hashtags in the tweets are used to identify certain political parties. 
Further the distribution of political affialiations of the tweets is visualized

o Grraphical figures (e.g. chart, graph, histogram, boxplot, word cloud, etc) are plotted that
visualizes some aspect of the generic tweets and alsofor the 2019 Canadian
elections tweets.

### 3-Model Preparation-

The generic tweets are split randomly into training data (70%) and test data (30%). Further the
data is prepared using three different type of features (Bag of words, N-Grams and TF-IDF) to try multiple classification algorithms (logistic regression, k-NN, Naive Bayes,SVM, decision trees, ensembles (RF, XGBoost)), where each tweet is considered a single observation/example. In these models, the target variable is the sentiment value, which is either positive or negative.  

### 4-Model Implementation-

Different models trained on the generic tweets are tested to obtain an accuracy value. Further all the trained models  
are used to predict the sentiments of Canadian elections tweets.

The model with best performance is choosen and the sentiment prediction results are visualized. Further the modelling results 
are compared with the original elections 2019 outcomes.Further the analysis of negative sentiment tweets is also carried out using the actual sentiment labels in the 2019 Canadian elections data.

### 5-Results

Finally, the analysis and interpretation of the results is discussed based upon how each political party is 
viewed in public based upon the predicted sentiment values. The approach of NLP analytics is discussed that 
whether it is useful or not for the political parties during the election campaigns


