Dataset API
============

A dataset instance is a collection of variables. A dataset is always part of a study.

Dataset
-------------------------

Represents a single dataset instance.

::

 /datasets/:id


Ressource Properties
~~~~~~~~~~~~~~~~~~~~~~
A dataset is represented by the following properties:

============  ============ 
Property      Type 
============  ============
id			  int
dataset_name  String
variables	  Collection<Variable>
?       	  ?
============  ============ 

Supported HTTP Methods: GET

Optional Parameters: None.

Dataset List 
-------------------------

Represents a list of all datasets.
:: 

/datasets

Supported HTTP methods: GET

Optional Paramters: None