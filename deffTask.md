### Задача 1
### Написать программу, которая последовательно вызывает три функции.
### Функция 1 – подсчитывает для заданного отрезка чисел все числа, которые делятся нацело
### на 3, функция 2 – подсчитывает для заданного отрезка чисел все числа, которые делятся
### нацело на 4, Функция 3– подсчитывает для заданного отрезка чисел все числа, которые
### делятся нацело на 5

```
def def3(d,f):
    if d > f:
        g=[f,d]
    else:
        g=[d,f]
    list1=[]
    list1.append(g[-1])
    while g[0] < g[1]:
        g[1] = g[1]-1
        list1.append(g[1])
        list2=[]
    for i in list1:
        if i % 3 == 0:
         list2.append(i)
    print(list2)

def def4(d,f):
    if d > f:
        g=[f,d]
    else:
        g=[d,f]
    list1=[]
    list1.append(g[-1])
    while g[0] < g[1]:
        g[1] = g[1]-1
        list1.append(g[1])
        list2=[]
    for i in list1:
        if i % 4 == 0:
         list2.append(i)
    print(list2)

def def5(d,f):
    if d > f:
        g=[f,d]
    else:
        g=[d,f]
    list1=[]
    list1.append(g[-1])
    while g[0] < g[1]:
        g[1] = g[1]-1
        list1.append(g[1])
        list2=[]
    for i in list1:
        if i % 5 == 0:
         list2.append(i)
    print(list2)


def5(1,20)

[20, 15, 10, 5]

```
