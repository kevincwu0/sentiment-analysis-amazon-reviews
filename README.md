# Sentiment Analysis NLP Amazon Reviews

Sentiment: how positive or negative some text is
Applicable to Amazon reviews, Yelp reviews, hotel reviews, tweets

Our data: http://cs.jhu.edu/~mdredze/datasets/sentiment/index2.html

### Outline of the sentiment analyzer
- Already classified as they are already marked "postive" and "negative"
- XML parser (BeautifulSoup)
- We'll need two passes, one to determine vocabulary size and which index corresponds to which word, and one to create data vectors
- Use any SkLearn classifier
- We'll use logistic regression so we can interpret the weights of the learn model to get the scores of each input word
