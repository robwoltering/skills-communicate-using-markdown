# This is a header

### This is a sub header

ttestt


![Image of Yaktocat](https://octodex.github.com/images/yaktocat.png)


``` python
ef merge(*args, missing_val = None):
#missing_val will be used when one of the smaller lists is shorter tham the others.
#Get the maximum length within the smaller lists.
  max_length = max([len(lst) for lst in args])
  outList = []
  for i in range(max_length):
    result.append([args[k][i] if i < len(args[k]) else missing_val for k in range(len(args))])
  return outList
```
