Study API
===========

A study instance is a collection of datasets.

Study
-------------------------

Represents a single study instance.

::

 /studies/:id


Ressource Properties
~~~~~~~~~~~~~~~~~~~~~~
A study is represented by the following properties:

===========  ============ 
Property     Type 
===========  ============
id			 String
study_name   String
datasets	 Collection<Dataset>
?			 ?
===========  ============ 

Supported HTTP Methods: GET

Optional Parameters: None.

Study List 
-------------------------

Represents a list of all studies.
:: 

/studies

Supported HTTP methods: GET

Optional Paramters: None

Included Datasets
-------------------------

::

/studies/:id/datasets 

Returns a list of all datasets associated with the specified study.

Supported HTTP methods: GET

Optional Paramters: None

Included Variables by Dataset
------------------------------

::

/studies/:id/datasets/:id/variables

Returns a list of all variables included in specified dataset and study.

Supported HTTP methods: GET

Optional Paramters: None

Included Variables
------------------------------
::

/studies/:id/datasets/variables

Returns a list of all variables included in specified study.

Supported HTTP methods: GET

Optional Paramters: None









