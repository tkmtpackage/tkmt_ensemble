Data Preprocessing:
===================
Data preprocessing is done using tools to assign input and output variables, data scaling, train test split. The performance is displayed in terms of accuracy, MAE, MSE, MAPE and RMSE and the actual vs predicted output is graphically represented. 

.. _importing:

Importing the library
------------

To use tkmt_ensemble.precrocessing, first import it:

.. code-block:: console

   from tkmt_package.preprocessing import Preprocessing

Creating recipes
----------------

To retrieve a list of random ingredients,
you can use the ``lumache.get_random_ingredients()`` function:

.. autofunction:: lumache.get_random_ingredients

The ``kind`` parameter should be either ``"meat"``, ``"fish"``,
or ``"veggies"``. Otherwise, :py:func:`lumache.get_random_ingredients`
will raise an exception.

.. autoexception:: lumache.InvalidKindError

For example:

>>> import lumache
>>> lumache.get_random_ingredients()
['shells', 'gorgonzola', 'parsley']
Data preprocessing is done using tools to assign input and output variables, data scaling, train test split. The performance is displayed in terms of accuracy, MAE, MSE, MAPE and RMSE and the actual vs predicted output is graphically represented. 
