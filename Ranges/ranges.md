## Ranges
In Python ```range``` is a list-constructor often used for driving for-loops or list comprehensions.

In Chapel, a range is a language construct which behaves and is used in much the same way as lists are used in Python.
###### Python
```Python

r1 = xrange(10, 20) # yields 10, 11, 12, 13, 14, 15, 16, 17, 18, 19
r2 = xrange(20, 10) # yields nothing

```

###### Chapel
```chapel
var r1 = 10..20; # yields 10, 11, 12, 13, 14, 15, 16, 17, 18, 19
var r2 = 20..10; # yields nothing

```
