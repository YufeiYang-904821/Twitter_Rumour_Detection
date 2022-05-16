# Twitter Rumour Detection Project
## Task 1: Rumour Detection
In this task, we are provided with a set of tweet IDs for the source tweets (i.e. the first tweet that started
the story) and their replies (i.e. the comments we saw in the figure above), and each source tweet is labelled
as either a rumour or non-rumour. The task here is to use the Twitter API to crawl the tweet IDs to get
the tweet objects, and then build a binary classifier to classify whether a source tweet is a rumour or not. A
tweet object provides a variety of information, including the text of the tweet, information of the user who
made the tweet, when the post was created, etc.
We explored the performance of Naive Bayes, Logistic Regression, Long Short-Term Memory, BERT and BERTweet 
models on classifying rumour tweets.

## Task 2: Rumour Analysis
In this task, we used our trained rumour classifier from the first task and apply it to unlabelled COVID-
19 tweets to detect rumours. Given the predicted rumours and non-rumours, we performed some analyses to 
understand the nature COVID-19 rumours and how they differ to their non-rumour counterparts.
