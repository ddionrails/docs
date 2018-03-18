Concept API
===========

A concepts represents a ???.  

Concept
-------------------------

Represents a single concept instance.

::

 /concepts/:id


Ressource Properties
~~~~~~~~~~~~~~~~~~~~~~
A concept is represented by the following properties:

============  ============ 
Property      Type 
============  ============
id            int
concept_name  String
label         String
?			  ?
============  ============ 

Supported HTTP Methods: GET

Optional Parameters: None.

Concept List 
-------------------------

Represents a list of all concepts.
:: 

/concepts

Supported HTTP methods: GET

Optional Paramters: None

Variables by concept
-------------------------

Get all variables with specified concept.
:: 

/concepts/:id/variables

Supported HTTP methods: GET

Optional Paramters: None

