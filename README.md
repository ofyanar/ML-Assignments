--------------------------------------Assignment 1--------------------------------------

 The first Machine Learning assignment

An implementation of the Nearest Neighbor methods for classification.

The datasets used were the built-in iris dataset from scikit-learn module of python, and the ionosphere dataset.

Nearest Neighbor method ran on both datasets we calculate the error rate it makes on our test set.

Finally we implement a conformal predictor based on the nearest neighbor conformity measure:

distance to nearest sample of a different class / distance to nearest sample of the same class

--------------------------------------Assignment 2--------------------------------------

 second machine learning assignment

this assignment contains an inductive conformal predictor for regression.

the datasets used were two variants of the diabetes dataset, the scikit-learn built-in version and the original dataset which can be found in 'https://hastie.su.domains/Papers/LARS/diabetes.data'

the training and test coefficient of determination is found for the Lasso model for both datasets.

they are then preprocessed using StandardScaler function while avoiding data snooping.

finally we implement an inductive conformal predictor, and found prediction interval for each test sample for significance levels 5% and 20%.

--------------------------------------Assignment 3--------------------------------------

 the last machine learning assignment

there are two datasets used in this assignment, the wine dataset which is buil into the scikit-learn module, and the USPS dataset of handwritten digits. (the training and test data can be found at the bottom ogf the page) https://hastie.su.domains/ElemStatLearn/

we estimate the generalisation-accuracy of the support vector machine (SVM) using cross validation on the training sets.

Additionally the error rate of the SVM is found using the default values of parameters of the SVM.
