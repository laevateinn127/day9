# day9
```
for e in range(100,1):
  print("*" * (e-1))
  for a in range(100,1,-1):
    print("*" * (e+1))
```
```
for e in range(10,-1,-1):
  print("*" * (e+1))
```
```
for x in range(1,10):
  for y in range(9,x,-1):
    print(' ',end='')
  for z in range(1,x,):
    print('*',end=' ')
  print('')
print("      * *")
print('      * *')
```
https://medium.com/@mingjunlu/understanding-for-loops-in-python-64dd993510ce
```
for i in range(5):
 print(i)
```
```
k = 1
  h = 1
  while k <6 :
    while h < 6:
    print (k,end=(''))
    h+=1
    k+=1
  h = 1 #為什麼要讓 h = 1
  print()
  
  for i in range(9,1,-3):
  print("")
  for j in range(1,10):
    print(i,end=(''))

for x in range(1,10):
  print (x,end='')
print ('')

for y in range(1,10):
  print (y,end="")

for x in range(1,10):
  print (x,end='')
  for y in range(1,10):
   print (y,end='')
  print ('')
  
for x in range(1,100):
  print(str(x)+'$$$$$$$$')
  
for a in range(*,10):
 print("")
 for b in range(1,10):
   print(b,end='')
```
