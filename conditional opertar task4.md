### Задание4
### Напишите программу, которая определяет пройдет коробка с размерами a*b*c в
### ящик с размерами x*y*z


```
a1,a2,a3=int(input("введите число")),int(input("введите второе число")),int(input("введите третье число")),
b1,b2,b3=int(input("введите число")),int(input("введите второе число")),int(input("введите третье число")),

if (a1>b1) and (a2>b2) and (a3>b3):
    print("да")
elif (a1>b2) and (a2>b1) and (a3>b3):
    print("да")
elif  (a1>b1) and (a2>b3) and (a3>b2):
    print("да")
elif (b1>a1) and (b2>a2) and (b3>a3):
    print("да")
elif (b1>a2) and (b2>a1) and (b3>a3):
    prit("да")
elif  (b1>a1) and (b2>a3) and (b3>a2):
    print("да")
else:
    print("нет")
```