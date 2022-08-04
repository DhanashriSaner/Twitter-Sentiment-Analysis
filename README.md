<h1>Tweets Sentiment Analysis using Machine learning </h1>
<h2>Introduction</h2>

Sentiment analysis refers to identifying as well as classifying the sentiments that are expressed in the text source. Tweets are often useful in generating a vast amount of sentiment data upon analysis. These data are useful in understanding the opinion of the people about a variety of topics.<br>
Therefore we need to develop an Automated Machine Learning Sentiment Analysis Model in order to compute the customer perception. Due to the presence of non-useful characters (collectively termed as the noise) along with useful data, it becomes difficult to implement models on them.<br>
In this project, we aim to analyze the sentiment of the tweets provided from the Sentiment140 dataset by developing a machine learning pipeline involving the use of three classifiers (Logistic Regression, Bernoulli Naive Bayes, and SVM)along with using Term Frequency- Inverse Document Frequency (TF-IDF). The performance of these classifiers is then evaluated using accuracy and F1 Scores.<br>

<h2>Problem Statement</h2>
In this project, we try to implement a Twitter sentiment analysis model that helps to overcome the challenges of identifying the sentiments of the tweets. The necessary details regarding the dataset are:<br>
The dataset provided is the Sentiment140 Dataset which consists of 1,600,000 tweets that have been extracted using the Twitter API. The various columns present in the dataset are:<br>
target: the polarity of the tweet (positive or negative)<br>
ids: Unique id of the tweet<br>
date: the date of the tweet<br>
flag: It refers to the query. If no such query exists then it is NO QUERY.<br>
user: It refers to the name of the user that tweeted<br>
text: It refers to the text of the tweet<br><br>

<h3>Dataset used </h3> <br>
<a href = "https://www.kaggle.com/datasets/kazanova/sentiment140">Sentiment140 dataset with 1.6 million tweets</a>

<h2>Project Pipeline</h2>
The various steps involved in the Machine Learning Pipeline are :<br>
Import Necessary Dependencies<br>
Read and Load the Dataset<br>
Exploratory Data Analysis<br>
Data Visualization of Target Variables<br>
Data Preprocessing<br>
Splitting our data into Train and Test Subset<br>
Transforming Dataset using TF-IDF Vectorizer<br>
Function for Model Evaluation<br>
Model Building<br>
Conclusion<br>
