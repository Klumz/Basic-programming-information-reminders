Whole example:

```
magicNumber = 25

for n in range(101):
    if n is magicNumber:
        print(n, "is the magic number!")
        break
    else:
        print(n)
```


```
magicNumber = 25

# This bit is going from 0-100 in order to find the magic number, which is 25.
for n in range(101):

    if n is magicNumber:
    
        # Once the magic number is found, print it with a string.
        print(n, "is the magic number!")
        
       # This stops the loop from continuing after 25, so it causes less strain and memory.
        break
        
    else: 
        print(n)
```
