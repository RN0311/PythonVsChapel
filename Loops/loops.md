## Loops
###### Python
```Python

for i in range(1,10):
  print(i)
  
  
for i,v enumerate(['cat','mat','hat']):
  print(i,v)  
```
###### Chapel
```Chapel
for i in 1..10{
  writeln(i);
}

for (i,v) in zip(1.., ['cat','mat','hat']){
  writeln(i, ' ',v);
}
```


