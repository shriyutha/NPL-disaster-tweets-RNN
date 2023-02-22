# NPL-disaster-tweets:


## Simple RNN model:

The Kaggle competition page can be found here: https://www.kaggle.com/competitions/nlp-getting-started

The data can be found here: https://www.kaggle.com/competitions/nlp-getting-started/data



## Table of Contents:

* Intoduction
* Brief Description of the Problem and Data
* Exploratory Data Analysis
* Model Architecure
  * LSTM
  * GRU
* Results and Analysis
* Conclusion


### Introduction:

Natural disasters can have devastating impacts, both in terms of human lives and economic losses. Early detection of these events can be crucial in preventing their devastating consequences and one of the most promising technologies in this regard is the analysis of tweets on Twitter. There are several advantages in using Social Media to get help in this kind of situations, such as their ability to quickly provide a large amount of data, their global reach, and their ability to capture more spontaneous reactions from users, and Twitter is amongst the most popular. This makes it an invaluable tool for disaster detection, as it can provide information about the scale and severity of events much more quickly than traditional methods. By using Twitter for disaster detection, emergency responders can act more quickly and effectively in response to disasters, thus reducing their devastating impacts.

### Brief Description of the Problem and Data:

In this Notebook, we focused on trying to be able to differentiate between a regular, random Tweet from an one that is about a Natural Disaster.
The main aim for this Notebook is to start practicing with Natural Language Processing, starting from the preprocessing phase all the way to the evaluation of the results phase.

There are 7613 entries (or rows) and five columns: id, keyword, location, text, target. The text column holds the tweet text which we will need to evaluate. We see that the text cells contain all sorts of characters such as lowercase letters, uppercase letters, numbers, punctuation, hastags (#), etc.

The Target is whether or not the text/tweet is a real disaster or not.

### LSTM model heatmap:

<img width="538" alt="Screen Shot 2023-02-22 at 2 15 35 PM" src="https://user-images.githubusercontent.com/81925727/220772410-d2bf4269-a46d-40df-8d13-d954f472b787.png">


### GRU model heatmap:

<img width="538" alt="Screen Shot 2023-02-22 at 2 15 45 PM" src="https://user-images.githubusercontent.com/81925727/220772352-3dabafd1-9589-4dc7-b262-3067a785683a.png">


### Competation results:

The first model using LSTM techniques got an F1 score of 0.556, which is better than the GRU model which got an F1 score of 0.541 on the test set. These values are a bit better than randomly guessing.

![Screen%20Shot%202023-02-22%20at%201.42.31%20PM.png](attachment:Screen%20Shot%202023-02-22%20at%201.42.31%20PM.png)


![Screen%20Shot%202023-02-22%20at%201.42.52%20PM.png](attachment:Screen%20Shot%202023-02-22%20at%201.42.52%20PM.png)
