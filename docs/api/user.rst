User API
========

A user instance represents a person who has registered with ddionrails.   

User 
-------------------------

Represents a single user instance.

::

 /users/:id


Ressource Properties
~~~~~~~~~~~~~~~~~~~~~~
A user is represented by the following properties:

===========  ============ 
Property     Type 
===========  ============
id           int
email        String
is_active    boolean
date_joined  timestamp 
username     string 
===========  ============ 

Supported HTTP Methods: GET

Optional Parameters: None.

User List 
-------------------------

Represents a list of all users.
:: 

/users

Supported HTTP methods: GET

Optional Paramters: None