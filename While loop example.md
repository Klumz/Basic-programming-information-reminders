Whole example:
```
insertvariablehere = 5

while insertvariablehere < 10:
    print(insertvariablehere)
    insertvariablehere += 1
```

Without "insertvariablehere += 1":

```
insertvariablehere = 5

# 5 < 10 is true, so this will print "5" infinitely
while insertvariablehere < 10:
    print(insertvariablehere)
```

With "insertvariablehere += 1":

```
# This example adds +1 after printing out "5" each time, stopping the infinite loop.
while insertvariablehere < 10:
    print(insertvariablehere)
    insertvariablehere += 1
```
