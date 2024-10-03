1. The code normalizes the data set, adding more pulsar values to reduce the skewness of the data set
2. It then uses logistic regression from sklearn to identify pulsars from the testing dataset
3. And runs sklearn's evaluation functions; to provide the model's performance metrics; logistic regression was found to work better than linear regression for this case.
(The datasets were initially cleaned and checked for null values, before being split into testing and training data)
