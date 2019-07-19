## Exercise I


```
a) O(n) since it doesn't matter what the amount is only that the calculation runtime is linear, that is it only runs through one time.
```


```
b) O(n^4) the first loop is O(n) and every nested loop adds and exponent to that so since there are three nested loop the exponent is four.
```

```
c)  O(n) calling the function recursively is still a linear run time.
```

## Excercise II

*Binary Search*
Start on the middle floor and drop the egg
  if egg breaks adjust the scope of floors to be tested to that floor and below
Repeat until egg doesn't break
  if the number of floors to be tested is 3 or 1 _f_ is that floor plus one
  else keep repeating

runtime is O(log n)
