#Solution to if exercises in snakify

##1. Odd numbers:
![problem 1](https://user-images.githubusercontent.com/89052189/132270975-78b38e43-4b0c-4d87-b14f-0b14aa4d7902.png)


```.py
# Read an integer
a = int(input())
b = int(input())

if a>b:
    print(b) # a is less than b

else:
    print(a) #b is less than a
    
#END
```

##2.Sign function:
![problem 2](https://user-images.githubusercontent.com/89052189/132271104-b5e68ffd-00ee-4a6e-8d62-a632435a0cc6.png)

```.py
# get input 
x = int(input())

if x > 0:
    print(1)
    
elif x < 0:
    print(-1)
    
else: 
    print (0)
    
#END
```

##3.Minimum of 3 numbers:
![problem 3](https://user-images.githubusercontent.com/89052189/132271169-209ca3fb-888e-499c-9691-af2379ed58af.png)
```.py
# Read an integer:
a = int(input())
b = int(input())
c = int(input())

if c < a and c < b:
    print (c)

if a < b and a < c:
    print(a)
    
elif b < c and b < a:
    print (b)
#END
```

##4.Equal numbers: 
![problem 4](https://user-images.githubusercontent.com/89052189/132271221-e100472c-49e2-4351-a0a8-206516acbaed.png)

```.py
a = int(input())
b = int(input())
c = int(input())

if a==b==c:
    print(3)

elif a==b!=c or a==c!=b or b==c!=a:
    print(2)
    
else:
    print(0)
#END
```

##5.Rook move:
![problem 5](https://user-images.githubusercontent.com/89052189/132271260-5ae3e5df-3aad-4c63-ad3b-11ef839d5472.png)

```.py
a = int(input())
b = int(input())
c = int(input())
d = int(input())

if a==c or b==d:
    print ("YES")
    
else: 
    print("NO")
#END
```

##6. Chess board- same color:
![problem 6](https://user-images.githubusercontent.com/89052189/132271295-41b687dd-c24f-42cb-9f89-e647c1d95e03.png)

```.py
a = int(input())
b = int(input())
c = int(input())
d = int(input())

if (a + b) %2 == (c + d) %2: 
    print ('YES')


else:
    print('NO')
#END
```

##7.King move:
![Problem 7](https://user-images.githubusercontent.com/89052189/132271311-3a17e749-5874-42f6-9956-1d6d9086a137.png)

```.py
a = int(input())
b = int(input())
c = int(input())
d = int(input())

if abs(a-c) <= 1 and abs(b-d) <= 1:
    print('YES')
    
else:
    print('NO')
#END
```
##8.Bishop move:
![problem 8](https://user-images.githubusercontent.com/89052189/132271328-ef752473-0363-4c2f-afa8-ebb604adeb03.png)

```.py
a = int(input())
b = int(input())
c = int(input())
d = int(input())

if abs(a-c) == abs(b-d):
    print('YES')

    
else:
    print('NO')
#END
```

##9.Queen move:
![Problem 9](https://user-images.githubusercontent.com/89052189/132271371-3c78217c-f66f-4152-b25e-b6813166a9d8.png)

```.py
a = int(input())
b = int(input())
c = int(input())
d = int(input())

if a == c or b == d or abs(a-c) == abs(b-d):
    print('YES')
    
else: 
    print('NO')
#END
```

##10.knight move:
![problem 10](https://user-images.githubusercontent.com/89052189/132271404-18937e91-9e77-40d9-b24c-cf8842bb1cd9.png)

```.py
a = int(input())
b = int(input())
c = int(input())
d = int(input())
d1 = abs(a - c)
d2 = abs(b - d)
if d1 == 1 and d2 == 2 or d1==2 and d2 ==1:
    print('YES')
    
else:
    print('NO')
#END
```

##11.Chocolate bar:
![Problem 11](https://user-images.githubusercontent.com/89052189/132271431-1d3deee1-223a-4892-b24c-0aa7c0a32720.png)

```.py
n = int(input())
m = int(input())
k = int(input())

if k < n * m and ((k % n == 0)or (k % m == 0)):
    print('YES')
    
else: 
    print('NO')
#END
```

##12.Leap year:
![Problem 12](https://user-images.githubusercontent.com/89052189/132271453-af18224b-f726-4bde-8eab-8f50d7eb84af.png)

```.py
a = int(input())

if (a % 4) == 0 and not (a % 100) == 0 or(a % 400) ==0:
    print('LEAP')
       
else: 
    print('COMMON')
#END
```
