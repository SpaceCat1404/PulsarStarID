(I couldn't find the cleaning files, but the datasets were initially cleaned and checked for null values, before being split into testing and training data)
The code normalizes the data set, adding more pulsar values to reduce the skewness of the data set
It then uses logistic regression from sklearn to identify pulsars from the testing dataset
And runs sklearn's evaluation functions; to provide the model's performance metrics; logistic regression was found to work better than linear regression for this case.
