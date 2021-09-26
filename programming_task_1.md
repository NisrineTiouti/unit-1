```.py
#Ask the user for 2 numbers a and b
#Check if one of them is 10 or if their sum is 10 
list = [a, b]
print("Enter 2 numbers: ")
a = input()
b = input()

if '10' in list:
  print(f"Makes10({a}, {b})-->True")
  if '10' not in list:
    print(f"Makes10({a}, {b})-->False")
  
elif int(a) + int(b) == 10:
  print(f"Makes10({a}, {b})--> True")
else:
  print(f"Makes10({a}, {b})--> False")
  
#END
```
![Capturecode](https://user-images.githubusercontent.com/89052189/134808242-0ffd856c-0a3c-4ee1-b6ca-fc2c772a9eff.PNG)
![Capturecode2](https://user-images.githubusercontent.com/89052189/134808253-b1a503f4-531a-4600-a487-061061633c3b.PNG)
![Capture44](https://user-images.githubusercontent.com/89052189/134808503-d1ea4a71-4936-483e-a5d6-25256ae35e9f.PNG)
