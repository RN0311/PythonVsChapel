Python does not support switch-statements and instead relies on chaining ```if-elif-else``` statements. <br >
Chapel, on the other hand, does have switch-statements, specifically ```select-when-otherwise``` statements.

###### Python
```Python
if beard_color == "white":
  print "Oh.Then he must have thrown curd on them.As always."
elif beard_color  == "blue":
  print "Oh.He must have had alot of fishes then, hence adapted that color"
elif beard_color == "red":
  print "CAUTION!""
else:
  print "Yay!He is still young."
```
###### Chapel
```Chapel
writeln("What is the color of chotu's beard?");

var beard_color = read(string);
select(beard_color) {
  when "blue" {
    writeln("Oh.He must have had alot of fishes then, hence adapted that color.");
    }
  when "red" {
    writeln("CAUTION!");
    }
  when "white" {  
    writeln("Oh.Then he must have thrown curd on them.As always.");
    }
  otherwise {
    writeln("Yay! He shaved them all :P!");
    }
}
```

