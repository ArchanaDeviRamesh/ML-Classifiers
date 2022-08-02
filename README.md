# ML-Classifiers
Performance analysis of various machine learning classifiers in predicting Cardio Vascular disease 

The data.csv file given is downloaded from https://www.kaggle.com/raminhashimzade/cardio-disease

Problem Definition:

* This work aims to analyze and compare performance of various machine learning classification algorithms viz. Decision Tree, Random Forest, Naive Bayes, Stochastic Gradient Descent, Logistic Regression and K Nearest Neighbours for predicting cardio disease. 

* First the relevant features are collected using the feature selection method, Sequential Floating Backward Selection and then these are given as inputs to the machine learning algorithms. 

* Accuracy of the models were calculated using stratified K fold cross validation method.

* For analysing and comparing the performance, the evaluation metrices Accuracy, Precision, Recall and F1 were used. 

* Hyperparameter tuning was also done using GridSearch.

* A performance analysis was also made using AUC-ROC curve.

Results:

* The classifier Decision Tree gave the best performance with 72.45%.
