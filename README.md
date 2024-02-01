# NLP-TOXIC-TWEET-PREDICTION
Use NLP and ML to make a model to identify toxic and non-toxic tweets.
Steps
1.	Load the tweets file using the read_csv function from the Pandas package.
(downloaded from https://www.kaggle.com/datasets/ashwiniyer176/toxic-tweets-dataset.)
2.	Upload the tweets into a list for easy text cleanup and manipulation
3.	Clean up the tweets using regular expressions and tokenizer and apply lemmatization
4.	Join the tokens back to form strings, which will be required for the vectorizers
5.	Assign X and y
6.	Perform train_test_split using sklearn Task to Perform
7.	Use TF-IDF values for the terms as a feature to get into a vector space model
8.	Fit and apply the vector space model on the train set and test set
9.	Apply ensemble learning to use the given  machine learning algorithms.
  Decision Trees
• Random forest
• Naive Bayes Model
• K-NN Classifier
• SVM
10.	Make predictions for the train and the test sets 
11.	Model evaluation: accuracy, recall, and f_1 score
12.	Building Confusion Matrix and RoC - AUC curve

