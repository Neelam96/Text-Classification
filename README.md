# Text-Classification Using Naive Baiyes
Classify files into one of a 20 classes using Naive Baiyes

## Problem statement
Task was to:

1. Perform Test Classification using Multinomial Naive Bayes(already implemented in sklearn).
2. Implement Naive Bayes on your own from scratch for text classification. 
3. Compare Results of your implementation of Naive Bayes with one in Sklearn.

Dataset - http://archive.ics.uci.edu/ml/datasets/Twenty+Newsgroups

## Using this repository

1. I have used "Project_Text_Classification1.ipynb" to save data into files "X.txt" and "Y.txt"
2. Reading of above said two files is being done in "Project_Text_Classification2.ipynb".
3. As Y_pred value was taking too much time. So, I stored that in 'Y_pred_my_clf.npz' file and used it in my Naive Baiyes Classifer implementation.

- Note: X.txt is not uploaded because it's size was >25MB

OR

You can use "Project_Text_Classification.ipynb" which does the above same task without any file reading and writing

## Results obtained

1. f1-score: 0.82 using Naive Bayes from sklearn
2. f1-score: 0.92 using Naive Bayes from scratch

f1-score obtained from this repo's Naive Bayes implementation from scratch is better than that of obtained from sklearn's implementation
