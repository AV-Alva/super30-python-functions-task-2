## Concepts Learned

### *args
`*args` allows a function to accept any number of positional arguments.
The supplied values are stored as a tuple.

Example:

calculate_total(10, 20, 30)

Here, numbers becomes:

(10, 20, 30)


### **kwargs
`**kwargs` allows a function to accept any number of keyword arguments.
The supplied values are stored in a dictionary.

Example:

create_profile(name="Rahul", age=22)


### Lambda
A lambda is a short anonymous function used for simple operations.

Example:

square = lambda x: x * x


### map()
`map()` applies a function to every item in an iterable.

Example:

map(lambda x: x * x, numbers)


### filter()
`filter()` selects only the items that satisfy a condition.

Example:

filter(lambda x: x % 2 == 0, numbers)


### Recursion
Recursion occurs when a function calls itself.

Every recursive function should have a base case that stops further
recursive calls.


### Local Scope
A local variable is created inside a function and is normally accessible
only inside that function.


### Global Scope
A global variable is created outside functions and can be accessed by
different parts of the program.
