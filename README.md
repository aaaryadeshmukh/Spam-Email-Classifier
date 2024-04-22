# Spam-Email-Classifier
Spam Mail Detection in Python:
This code implements a spam mail detection system using a logistic regression model. The model is trained on a dataset of spam and ham emails, and then it is used to predict whether a new email is spam or ham.

The code is divided into the following steps:

1. Import the necessary libraries.
2. Load the dataset of spam and ham emails.
3. Clean the dataset by removing punctuation and converting all letters to lowercase.
4. Split the dataset into training and test sets.
5. Create a TfidfVectorizer to extract features from the emails.
6. Train a logistic regression model on the training set.
7. Evaluate the model on the test set.
8. Print the accuracy of the model on the training and test sets.
9. Enter a new email and predict whether it is spam or ham.
10. The following are some of the key features of the code:

The code uses a logistic regression model to classify emails as spam or ham. Logistic regression is a simple but effective model that is often used for text classification tasks.
It also uses a TfidfVectorizer to extract features from the emails. TfidfVectorizer is a popular method for extracting features from text data. It works by assigning a weight to each word in an email based on its frequency and importance.
Moreover, it evaluates the model on a test set to get an unbiased estimate of its accuracy. This is important because the accuracy of a model can often change when it is evaluated on a different dataset.
The code allows the user to enter a new email and predict whether it is spam or ham. This is useful for testing the model on new emails.

Additional Notes:
The dataset used in this code is available at https://archive.ics.uci.edu/ml/datasets/spambase.
The code can be easily modified to use a different dataset or a different machine learning model.
The code can be used to filter spam emails from your inbox.
The code can be used to build a spam detection web service.
