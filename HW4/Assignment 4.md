

```python
userinfo = input("What is your name?\t")
answer = userinfo[::-1] 
print(answer)

```

    What is your name?	Nishat
    tahsiN



```python
sum = 0
list = [1,2,3]
userinput=int(input("What number do you want to add?\t"))
list.append(userinput) 
for num in list:
    sum = sum +num

average  = sum / len(list)
print ("Average is: ", average )
```

    What number do you want to add?	5
    Average is:  2.75



```python
from math import pi
r = float(input("Enter the radius of circle : "))
print("Area of the circle with radius is: " + str(pi*r**2))


```

    Enter the radius of circle : 4
    Area of the circle with radius is: 50.26548245743669



```python
x = float(input("Enter a number: "))
from math import e
y = e**x
print(y)
print(math.log10(y))
```

    Enter a number: 6
    403.428793492735
    2.6057668914195107

