Basket API
============

Every user can have multiple baskets, where variables can be stored.

Basket 
-------------------------
Returns a basket instance. The owner of the basket must be logged in.

::

/baskets/:id

Ressource Properties
~~~~~~~~~~~~~~~~~~~~~~
A basket is represented by the following properties:

=============  ============ 
Property       Type 
=============  ============
id             int
basket_name    String
variable_list  Collection<Variable>
owner          User
study		   String
=============  ============ 

Supported HTTP Methods: GET, PUT, DELETE, 

Optional Parameters: None.

Basket List
-------------------------
Returns a list of all baskets belonging to the currently logged in user.
:: 

/baskets

Supported HTTP Methods: GET, POST

Optional Paramters: None

Variables List of a Basket
---------------------------
Returns a list of Variables associated with the specified basket.
:: 

/baskets/:id/variables

Supported HTTP Methods: GET, POST

Optional Parameters: None

Remove Variable from Basket
-----------------------
Removes the specified variable from the specified basket.
:: 

/baskets/:id/variables/:id

Supported HTTP Methods: DELETE

Optional Parameters: None






