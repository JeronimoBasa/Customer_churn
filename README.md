# Customer churn
Using Keras to assess customer churn with a simple dataset in Python. First we explored the data set and transform some of the variables in order to prepare them for the model. We define the model using a simple ANN with Keras and train it. Finally we compute some metrics and print the confusion matrix. After that, we repeat the process using Random Forest.

Note: this kind of datasets present imbalance, because usually there's a lot more clients that do not churn a service with respect to those who do. So we approach the imbalanced problem with a SMOTE technique.
