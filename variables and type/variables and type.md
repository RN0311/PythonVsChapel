## Variables and Types
In Python, variables are implicitly declared and their type determined when they are assigned to while in Chapel, variable
declaration is explicit, but the type of the variable can be inferred from its use in a manner equivalent to that of Python.
Let's see how:
###### Python
```Python
result = 10
money = 120.50
name = "Rashmi"
```
###### Chapel
```Chapel
var result = 10
var money = 120.50
var name = "Rashmi"
```

Types in Python are dynamic, i.e. a variable can change the type during its lifetime but for the type of a variable in
Chapel is static and inferred at compile-time, which means that a type is assigned and cannot be changed at runtime.

