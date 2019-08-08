# Predicition-Model-for-Viral-News-Articles
Model made to find the most important attributes of an article that will make it viral using scikit learn
Contributors: Felix Murray, Sean B. Lutu, Hannah Qureishi and myself.

main file contains the data loading and data preparation, data visualisation, and the plotting of the threshold between viral, popular 
and non viral articles.

The target variable is removed and the non viral articles are undersampled 
(as there are more of them than the viral and popular news articles)

To make the model, the processed data is split into 3 sets: the training set, the test set and the validation set. The model is made using 
a greedy approach, adding the next attribute that increases the overall accuracy of the model, however, still taking care not to over fit
the model.

A decision tree is also made given that it could also be argued that the model is non linear, and as such the tree was made to compare if 
it would increase the accuracy of the model.

functions file contains all the functions called in main to make the log reg model and carry out the forwards and backwards selection.

Our final logistic regression model yielded an accuracy of approximately 67%, which is very close to the results of K. Fernandes, P. Vinagre
and P. Cortez in their paper of "A Proactive Intelligent Decision Support System for Predicting the Popularity of Online News", in which
the same dataset is used. Their results range from 62% to 71% accuracy.

