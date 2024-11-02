### Задание1
### Напишите программу, которая по заданным границам отрезка, который указывает 
### пользователь, находит сумму всех четных чисел, произведение всех нечетных

```

a = int(input( " введите первую границу отрезка"))
b = int(input( " введите вторую границу отрезка"))

list1=[]
while a < b:
    b = b-1
    list1.append(b)


list2=[]
list3=[]
for i in list1:
    if i % 2 == 0:
        list2.append(i)
    else:
        list3.append(i)



print(sum(list2))


c=1
for d in list3:
    c*=d

print(c)

```