# Amazon-Food-Reviews-Analysis using Support Vector Machine

#### Performed Exploratory Data Analysis, Data Cleaning, Data Visualization and Text Featurization(BOW,TFIDF,AVG Word2Vec,TF-IDF W2V). 

SVM
1. Applied SVM with RBF(radial basis function) kernel on different text Featurization for data visualization. BOW,TFIDF, Avg-Word2Vec and TFIDF-Word2Vec 
2. Used both Grid Search & Randomized Search Cross Validation 
3. Evaluated the test data on various performance metrics like roc_auc, f1-score, precision, recall. also plotted Confusion matrix using seaborn.
4. Evaluated SGDClassifier on the best resulting featurization

###### Conclusions:
1. BOW Featurization with linear kernel with grid search gives the best result.
2. SGDClasiifier takes very less time to train.
<hr>
