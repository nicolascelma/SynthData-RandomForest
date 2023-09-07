# Synthetic Data With Random Forest Model
This notebook is an example of a synthetic data generator and a simple Random Forest Classifier. 

The first part demonstrates how to generate synthetic data for training the classifier.
The goal is to attain disease prediction, all through training a model on the synthetic data, in 
order to simulate real life research applications for such models, to be able to control and
experiment with the parameters, and reproduce the findings.

Later on, the model is trained and evaluated for accuracy and performance, through cross-validation 
and by comparing the predicted values to the true outcomes on a confusion matrix. Afterwards, I define
a hyperparameter tuning algorithm, which iterates over different hyperparameters on a grid, e.g. 
`n_estimators` or `max_depth`, testing different values and choosing the best configuration in the end.
