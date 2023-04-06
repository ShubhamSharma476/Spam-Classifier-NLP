# Spam-Classifier-NLP
This repository contains the code for a machine learning model for classifying SMS messages as spam or ham (not spam) using Naive Bayes classifier. 
The model was trained and tested on a custom dataset of SMS messages.

Dataset:

 The dataset used for this project contains SMS messages labeled as spam or ham. The dataset was preprocessed by removing stop words and stemming the 
 remaining words. The dataset was split into training and testing sets.

Data Preprocessing:

 Data cleaning and preprocessing were performed on the dataset to remove stop words and reduce words to their stem form. The NLTK library was used for 
 this purpose. The preprocessed text was then converted into a bag of words model using CountVectorizer from the scikit-learn library.

Model:

 The model used for this project was Naive Bayes classifier. The model was trained on the preprocessed data using the training set. 
 The accuracy of the model was calculated using the test set, and it achieved an accuracy of 98.39%.

Results:

 The final model achieved an accuracy of 98.39% on the test set, indicating that it is highly effective in classifying SMS messages as spam or ham. 
 This model could be further improved by using more advanced algorithms, such as neural networks, or by incorporating additional features, such as message 
 length or time sent.
