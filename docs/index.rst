.. sklean-genetic-opt documentation master file, created by
   sphinx-quickstart on Sat May 29 19:27:12 2021.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

sklean-genetic-opt
==================
scikit-learn models hyperparameters tuning, using evolutionary algorithms.
##########################################################################

This is meant to be an alternative from popular methods inside scikit-learn such as Grid Search and Randomized Grid Search.

Sklearn-genetic-opt uses evolutionary algorithms from the deap package to choose set of hyperparameters
that optimizes (max or min) the cross validation scores, it can be used for both regression and classification problems.

Installation:
#############

Install sklearn-genetic-opt

It's advised to install sklearn-genetic using a virtual env, inside the env use::

   pip install sklearn-genetic-opt

.. |PythonMinVersion| replace:: 3.7
.. |ScikitLearnMinVersion| replace:: 0.21.3
.. |NumPyMinVersion| replace:: 1.14.5
.. |SeabornMinVersion| replace:: 0.9.0
.. |DEAPMinVersion| replace:: 1.3.1
.. |PydanticMinVersion| replace:: 1.8.2
.. |MLflowMinVersion| replace:: 1.17.0

sklearn-genetic-opt requires:

- Python (>= |PythonMinVersion|)
- scikit-learn (>= |ScikitLearnMinVersion|)
- NumPy (>= |NumPyMinVersion|)
- Seaborn (>= |SeabornMinVersion|)
- DEAP (>= |DEAPMinVersion|)
- Pydantic (>= |PydanticMinVersion|)
- MLflow (>= |MLflowMinVersion|)

.. toctree::
   :maxdepth: 2
   :caption: User Guide / Tutorials:

   tutorials/basic_usage
   tutorials/callbacks
   tutorials/custom_callback
   tutorials/understand_cv
   tutorials/mlflow
   release_notes

.. toctree::
   :maxdepth: 2
   :caption: API Reference:

   api/gasearchcv
   api/callbacks
   api/plots
   api/mlflow
   api/space
   api/algorithms


.. toctree::
   :maxdepth: 1
   :caption: External References:

   external_references

Indices and tables
==================

* :ref:`genindex`
* :ref:`modindex`
* :ref:`search`

