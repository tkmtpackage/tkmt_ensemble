tkmt_package
=======================================

The tkmt_package is a Python library for dealing with regression problem statements. This package includes modules for ensemble learning starting from data preparation to assigning the dependent and independent variables, data normalization to rescale the data and train test split. There are modules for setting user defined base models to use ensemble learning techniques like averaging and weighted averaging. The module for the accuracy filter, filters out and displays the modules with the accuracy more than or equal to the set user defined threshold value. There is a module to get weights of the models defined by the user based on their accuracies. The module for averaging technique takes the average of the performance of all the models defined by the user and outputs a new model based on the average. Similarly, the module for weighted averaging, takes the average of all the models based on their weights. The module for performance evaluation shows the performance of the model in terms of accuracy, MAE, MSE, MAPE and RMSE. The performance of the models is plotted using the get_plot module in terms of real and predicted values.

Read the tutorial here:

https://docs.readthedocs.io/en/stable/tutorial/
