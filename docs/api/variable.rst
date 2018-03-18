Variable API
============

A variable instance represents a ???.

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
variable_name  String
dataset		   Dataset
study	       Study
analysis_unit  String
boost		   int
label          String
label_de	   String
period         int
sub_type       String
namespace	   String
...			   ...
=============  ============ 

Supported HTTP Methods: GET

Optional Parameters: None.

Variable List
-------------------------

Represents a list of all variables.
:: 

/variables

Supported HTTP Methods: GET

Optional Paramters:

=============  ============  =============================================
Parameter      Values        Description
=============  ============  =============================================
dataset	       dataset name  Variables included in specified dataset.
basket         basket id	 Variables included in specified basket.
=============  ============  =============================================

