Console Input/Output
We can write to the console (standard output) using ```write``` and ```writeln```.
###### Python
```Python
# With a newline
print "Hey, Rashmi and Aishwarya are working." 

# Without a newline
print "Hey, Rashmi and Aishwarya are working.", 
```
###### Chapel
```Chapel
// With a newline
writeln("Hey, Rashmi and Aishwarya are working."); 

// Without a newline
write("Hey, Rashmi and Aishwarya are working."); 
```

In Python one has to explicitly cast the input, whereas in Chapel the type of the input is 
provided to the read/readln functions directly.
