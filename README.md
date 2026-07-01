# special-method-repository
short note and codes on special methods in oops 

1. __init__() – Constructor
•	Automatically called when an object is created. 
•	Used to initialize object attributes.

2. __str__() and __repr__() – String Representation
•	__str__() returns a user-friendly string for print(). 
•	__repr__() returns the official or developer-friendly representation of an object. 


3. __len__() – Length
•	Allows the len() function to work with custom objects. 
•	Returns the number of items in an object. 

4. __eq__() – Equality
•	Defines how two objects are compared using the == operator. 
•	Returns True if the objects are considered equal; otherwise False. 
_
5. __add__(), __sub__(), __mul__() – Operator Overloading
•	Allow custom objects to use arithmetic operators. 
•	__add__() → + 
•	__sub__() → - 
•	__mul__() → * 

6. __getitem__() – Item Access
•	Enables indexing using square brackets []. 
•	Example: obj[0]. 

7. __setitem__() – Item Assignment
•	Allows values to be assigned using square brackets. 
•	Example: obj[0] = value. 

8. __contains__() – Membership Testing
•	Supports the in and not in operators. 
•	Determines whether an item exists in an object. 

9. __call__() – Callable Objects
•	Makes an object behave like a function. 
•	Allows the object to be called using parentheses (). 

10. __iter__() and __next__() – Iteration Support
•	__iter__() returns an iterator object. 
•	__next__() returns the next item during iteration. 
•	Used in for loops and with the next() function. 

11. __bool__() – Boolean Evaluation
•	Defines how an object is evaluated in a Boolean context. 
•	Used by bool(), if, and while statements. 
•	Returns True or False. 

12. __del__() – Destructor
•	Called when an object is about to be destroyed. 
•	Used for cleanup tasks, such as releasing resources. 
•	Its execution time is not guaranteed, so it should not be relied upon for critical cleanup.
