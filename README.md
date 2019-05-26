# Amazon-Fine-Food-Reviews

Amazon Fine Food reviews problem dealts with finding whether the review is positive or negative by using the given review 
text.

Since data is a text, the text is preprocessed to vectors by using various NLP techniques like BOW, TF-IDF, Avg W2v and TF-IDF
weighted W2v etc.

The metric used here is AUC and confusion matrix

The problem is benchmarked using Naive Bayes algorithm and then logistic regression is applied as linear model works 
well for high dimesional data
Tried some feature engineering to improve performance and implemented pertubation test for logistic regression to find
multi-collinear features
