Variable API
============

A variable instance represents a variable.

Variable 
-------------------------
Represents a single variable instance.

::

 /variables/:id

Ressource Properties
~~~~~~~~~~~~~~~~~~~~~~
A variable is represented by the following properties:

=============  ============ 
Property       Type 
=============  ============
id             int
name           string
dataset        string
study          string
analysis_unit  string
label          string
period         int
sub_type       string
=============  ============ 

Supported HTTP Methods: GET

Optional Parameters: None.

Variable List
-------------------------

Represents a list of all variables.
:: 

/variables

Supported HTTP Methods: GET

Optional Paramters: None