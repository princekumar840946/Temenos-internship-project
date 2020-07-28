# Temenos-internship-project
This is multi class classifier using various classification algorithms
We have been given Documents and scripts
The Documents are in html text and scripts are in key value pair like json format files,
So the task is to make  a classifier using Documents data and train it well using classificaton algorithms.
So the tedious task is to extract and train data on classification algorithm.
First we extract the data from the directory,and the data is in html format thus we extracted it using beautiful soup and then i did preprocessing it .
then a dataframe is ready but its a very small dataframe in terms of dimension which is hard to train so i used a function which make it little longer with the same dataframe,
and thus we used differrent classifiers to train .
Then we have script in json kind of format ,so first we convert in plain text and then preprocess,remove stop words,lemmatize and used as text data to know the labels.
