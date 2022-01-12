# Twitter Sentiment Analysis
Sentiment Analysis for Twitter comments from kaggle.

## Data source
Kaggle - [Twitter Sentiment Analysis](https://www.kaggle.com/jp797498e/twitter-entity-sentiment-analysis)

## Project Info
The data contains comments from twitter about provided entities. The task of this dataset is to judge the sentiment of the comments about the entity, based on 3 classes: positive, negative and neutral.


### Methods Used
* Logistic regression
* Decision Tree
* Naive Bayes
* Support Vector Classification

### Requirements
* Python 3.8.5
* sklearn 1.0
* numpy 1.21.2
* matplotlib 3.4.3
* seaborn 0.11.2
* wordcloud 1.8.1
* nltk 3.6.7

## Results
The following accuracies were obtained:
* Logistic regression = 0.83
* Decision Tree = 0.79
* Naive Bayes = 0.76
* Support Vector Classification = 0.86

As we can see, the best accuracy score was obtained with Support Vector Classification.
