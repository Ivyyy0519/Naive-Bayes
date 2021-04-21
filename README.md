# supervised-learning

Pose classification with naive Bayes
Yuxin Yan
Created for COMP30027 Machine Learning, sem 1, 2021, The University of Melbourne

To run Gaussian naive Bayes classifier, run the code blocks for the following functions: preprocess, train, predict
and evaluate. Then call each functions (example showed at the end of the noetbook).
1.Change the file location of 'preprocess' by location of training set, pass the result into 'train' (could name it train_set).
2.Pass the result of 'train' to 'predict' first argument (could name it train_info), change the second argument 
into testing set location, the third argument is the smoothing number used for GaussianNB (should be a negative number with large absolute value),
the default one is -50. This hyperparameter can be turned.
3.Pass the result of 'predict' to 'evaluate' (could name it pred), function 'evaluate' will print the accuracy.

To run KDE naive Bayes classifier, run the code blocks for Question 5. Then call each functions (example showed at the end of the noetbook).
1.Change the file location of 'preprocess' by location of training set, pass the result into 'train_KDE' (could name it train_set).
2.Pass the result of 'train_KDE' to 'pred_KDE' first argument (could name it train_info_KDE), change the second argument 
into testing set location, the third argument is the kernel bandwidth, the default is 10, it could be turned (5-25 is recommended).
The fourth argument is  smoothing number used for KDENB (should be a negative number with large absolute value),
the default one is -50. This hyperparameter also can be turned.
3.Pass the result of 'predict' to 'evaluate' (could name it pred_KDE), function 'evaluate' will print the accuracy.

To see the Macro-Micro metrics result, run the code blocks for Question 1.Then call each functions (example showed at the end of the noetbook).
1. Change the first argument of 'predictionTable' into the result of Naive Bayes predict function and pass it
into 'macroEvaluation' or 'microEvaluation' (could name it table).
2. Result of prediction table is a confusion matrix and is printed.
