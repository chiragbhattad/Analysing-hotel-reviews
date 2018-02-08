# Analysing-hotel-reviews
Using Gaussian NaiveBayes to create a model that can analyse the hotel reviews with an accuracy of at least 75%.

# CountVectorizer
CountVectorizer counts the frequency of the words used and tokenizes them. If you do not provide an a-priori dictionary and you do not use an analyzer that does some kind of feature selection then the number of features will be equal to the vocabulary size found by analyzing the data.

#TF-IDF
Term Frequency-Inverse Document Frequency is a numerical statistic that is intended to reflect how important a word is to a document in a collection or corpus. The tf-idf value increases proportionally to the number of times a word appears in the document, but is often offset by the frequency of the word in the corpus, which helps to adjust for the fact that some words appear more frequently in general.


The following steps were followed to use Gaussian NaiveBayes model to analyse Hotel reviews:

1. Read and review the training data set
2. Clean the data and remove the Is_Response column.
3. CountVectorizer and TF-IDF are the two methods of Textual analysis which are worked on.
4. Converting the data into numerical format to tinker it and run the Gaussian NaiveBayes model on.
5. Dividing the dataset into Train and Test and run the model on both set of data (CountVectoriser and TF-IDF)
6. Save the final result into a new csv file.
