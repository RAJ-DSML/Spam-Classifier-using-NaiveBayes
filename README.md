# Spam Classifier using NaiveBayes

<!-- Description -->
### Description

In this notebook I use the Naive Bayes Algorithm. It is a classification technique based on Bayes' Theorem with an assumption of independence among predictors. About the data set I used SMS Spam Collection Data Set. Using Naive Bayes classification algorithm my model correctly classified total of 1086 messages with the 97% accuracy. So, Naive Bayes algorithm basically a Machine Learning technique but I first use the nltk libraries and performed some NLP techniques like text cleaning, lemmitization and then I split the whole data and fit into the Naive Bayes model to predict the messages whether it is a Spam or Ham.

### Prerequisites

You need to install following python packages along with Jupyter Notebook.

* sklearn
  ```sh
  pip install -U scikit-learn
  ```
* nltk
  ```sh
  pip install nltk
  ```
  
### Data Set Source  
Link --> https://archive.ics.uci.edu/ml/datasets/SMS+Spam+Collection
