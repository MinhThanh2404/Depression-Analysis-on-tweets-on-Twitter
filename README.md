# Depression-Analysis-on-tweets-on-Twitter
This is the group final project of Natural Language Processing subject. We are asked to apply NLP techniques to process the raw text data and some classification models to analyze whether each tweet on Twitter is negative or positive.
## About the dataset
The data includes more than 1 million tweets on Twitter written in English, with 6 variables:
* target: the label of the tweet (0 = negative, 2 = neutral, 4 = positive)
* ids: the ID of the tweet
* date: when the tweet was upload
* fla: query
* user: the username of the account uploading the tweet
* text: the content of the tweet
Due to the grand size of the spreadsheet file, it is unable to upload on Github. Here is the Kaggle link of the data: https://www.kaggle.com/datasets/kazanova/sentiment140
## Workflow:
1. Import the data
2. Mostly apply NLP techniques to process the text data
3. Visualize the data
4. Split into training set and testing set
5. Build and train 2 classification models: SVM, Decision Tree Classifier
6. Analyze the result of testing set

*The report is written in Vietnamese. In short, some NLP techniques we used were lowercasing text, replacing repeating text, removing stopwwords, tokenization, lemmatization, emoji processing,..., most of whose function were built in sklearn library. The evaluation indicated that SVM classified better, with the accuracy percentage was approximately 70%. I am trying to improve the model for a higher accuracy, and challege with other languages, such as Vietnamese.*
