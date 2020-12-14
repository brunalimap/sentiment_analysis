# Analysis of sentiments
***


## About the Dataset

This dataset was taken from the social network Twitter and is divided into three classes (positive, negative and neutral). These dataset have a popular language with slang and word abbreviations. It is necessary to perform some manipulations on the data to obtain a better performance of the model used.

Sentiments labels were transformed as follow:

- Negative label: 0
- Positive label: 1
- Neutral label: 2

link of the dataset: https://www.kaggle.com/augustop/portuguese-tweets-for-sentiment-analysis


## Columns description

- <b>id:</b> String identifier directly from Twitter;
- <b>tweet_text:</b> Full text from the tweet
- <b>tweet_date:</b> Tweet creation date
- <b>sentiment:</b> Sentiment label (classifier)
- <b>query_used:</b> Query used to collect the tweet



## References

- https://www.kaggle.com/leandrodoze/sentiment-analysis-in-portuguese 
- https://linguistic-datasets-pt.etica.ai/ 
- https://lionbridge.ai/datasets/best-portuguese-language-datasets-for-machine-learning/ 
- https://docs.python.org/3/library/re.html
- https://docs.python.org/pt-br/3.8/howto/regex.html
- https://gist.github.com/alexandreservian/124db2fab8a75474dd6fdc4f17f93a5d
- https://scikit-learn.org/stable/modules/naive_bayes.html#multinomial-naive-bayes