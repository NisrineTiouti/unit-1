##Loop exercises solutions:

#1.Series- 1:
![series-1](https://user-images.githubusercontent.com/89052189/132375018-b37c4cd1-4f81-4ccc-b60d-71edef74fa49.png)

```.py
a = int(input())
b = int(input())
for i in range(a, b+1):
    print(i)
#END
```

#2. Series- 2:
![series-2](https://user-images.githubusercontent.com/89052189/132379609-a3bd10ff-205f-4328-96bc-788d54bb43d6.png)

```.py
a = int(input())
b = int(input())

if a<b:
    for i in range(a, b+1):
        print(i)
    
if a>= b:
    for i in range(a, b-1, -1):
        print(i)
#END
```

#3. Sum of ten numbers:

![loop flowcharts (6)](https://user-images.githubusercontent.com/89052189/132395343-8a014bcd-2f69-45f0-bee3-479776760834.png)


```.py
n = 0


for num in range(10):
    n+= int(input())
    
print(n)
#END

#4.Sum of N numbers:
![loop flowcharts (7)](https://user-images.githubusercontent.com/89052189/132396620-a66fa083-88ab-4b59-9f20-712e20fd047f.png)

```.py
n = int(input())
sum = 0


for num in range(n):
    sum += int(input())
    
    
print(sum)
#END
```

#5. sum of cubes:

![loop flowcharts (8)](https://user-images.githubusercontent.com/89052189/132395704-d7fa7236-824c-45d5-88cb-c0d789b25555.png)

```.py
sum = 0
n = int(input())

for i in range(1, n+1):
    sum += i**3
    
print(sum)
#END
```
#6. Factorial:

![loop flowcharts (9)](https://user-images.githubusercontent.com/89052189/132396563-960b6bc4-7ab5-44da-bbf4-1dc6fec8cba2.png)

```.py
sum = 1
n = int(input())

for i in range(1,n+1):
  sum *= i

print(sum)
```
#7. The number of zeros

![loop flowcharts (5)](https://user-images.githubusercontent.com/89052189/132394534-35f6b86a-dcca-431d-9063-f04b6d134771.png)


```.py
sum = 0
for i in range(int(input())):
   if int(input()) == 0:
       
    sum += 1
print(sum)
#END
```

#8.Adding factorials

![adding factorials](https://user-images.githubusercontent.com/89052189/132392864-52254623-a776-439f-9737-fada9c4d7cf4.png)

```.py
sum = 1
sum2 = 0
n = int(input())

for i in range(1, n+1):
    sum *= i 
    sum2 += sum 
    
print(sum2)
#END
```

#9. Ladder

![loop flowcharts (10)](https://user-images.githubusercontent.com/89052189/132401790-8b542fb7-dc2f-43a0-b0bf-af93b7569fa1.png)

```.py
n = int(input())

for i in range(1, n+1):
    for j in range(1):
        print(" ", end='')
        for k in range(1,i+1):
            print(k, end='')
        


#END
```
#Lost card:
![loop flowcharts (11)](https://user-images.githubusercontent.com/89052189/132435870-ffdbe578-0241-447e-ae94-4fde0b527c67.png)

```.py
n = int(input())
sum = 0
for i in range (1, n+1):
    sum += i
for i in range(n - 1):
    sum -= int(input())
print(sum)
    
#END
```

