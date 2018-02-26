## Conditionals and Blocks

Python maintains its' indentation guided block-structure.
###### Python
```Python
beard_color = raw_input("What is the color of chotu's beard?\n")

if beard_color  == "blue":
  print "Oh.He must have had alot of fishes then, hence adapted that color"
  
  
if beard_color == "white":
  print "Oh.Then he must have thrown curd on them.As always."
else:
  print "Yay!He is still young."
  
  
if beard_color == "white":
  print "Oh.Then he must have thrown curd on them.As always."
elif beard_color == "red":
  print "CAUTION!"
  
  
if beard_color == "white":
  print "Oh.Then he must have thrown curd on them.As always."
elif beard_color == "red":
  print "CAUTION!""
else:
  print "Yay!He is still young."
```

###### Chapel
```Chapel
writeln("What is the color of chotu's beard?\n");
var beard_color = read(string);
if beard_color  == "blue" {
  writeln("Oh.He must have had alot of fishes then, hence adapted that color");
}


if beard_color  == "blue" {
  writeln("Oh.He must have had alot of fishes then, hence adapted that color");
} else {
  writeln("Yay!He is still young.");
}


if beard_color  == "blue" {
  writeln("Oh.He must have had alot of fishes then, hence adapted that color");
} else if beard_color == "red" {
    writeln("CAUTION!");
}


if beard_color  == "blue" {
  writeln("Oh.He must have had alot of fishes then, hence adapted that color.");
} else if beard_color == "red" {
    writeln("CAUTION!");
} else {
    writeln("Oh.Then he must have thrown curd on them.As always.");
}
```
  
