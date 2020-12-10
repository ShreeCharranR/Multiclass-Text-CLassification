# The BBC News Clustering
* The dataset has 2225 News and all are labeled.
* There are 5 different categories for these news.
* Even though the news are labeled, they will be used to test it after prediction.
* The all labels will be predicted by unsupervised learning.

![dist](/graph.PNG)

## Word 2vec V/S   TFIDF 
* The two different libraries are used to predcit news' classes.
* **1)** Word2Vec 
* * Firstly, the prediction is done without cleaning the words, just stopwords will be removed. 
* * Also, the two different stem algorithms will be used to clean words and will be compared all results. 
* * The purpose of stemming is removing inflection in words. For expample, 'loves' ---> 'love'
* * The stemming libraries ---> WordNetLemmatizer and PorterStemmer (There are more than these 2)
* * Lastly, nltk.kmeansclusterer library is used to predict clusters.
* **2)** TfidfVectorizer
* * This library more convenient than first one because we didn't use any stemming algorithm because it is not necessary.
* * Kmeans library is used to predict clusters.

![2](/wordcloud.PNG)

![1](/cluster.PNG)


# ANN

- Direct prediction
- Parameter tuning
