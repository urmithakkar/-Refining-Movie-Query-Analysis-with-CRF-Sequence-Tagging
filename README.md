# -Refining-Movie-Query-Analysis-with-CRF-Sequence-Tagging

This project involves optimizing the performance of a **Conditional Random Field (CRF) sequence tagger** for movie trivia questions and answers data, which consist of instances of data of word sequences with the target classes/labels for each word in a **BIO (Beginning, Inside, Outside)** tagging format. 

It involves reading in, pre-processing, training and developing our tagger on the training data from *trivia10k13train.bio.txt*, and finally testing our tagger on the data *trivia10k13test.bio.txt*, attempting to get the best performing tagger across the different labels in our development process. We are going to optimize the performance of the tagger by improving its feature extraction function on the word sequences, incorporating POS tagging first, then the final task is to optimize the performance by all legal means neccessary (except looking at the test data).
