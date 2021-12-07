## 1 задание
```python
print('y w x z')
for x in 0,1:
  for y in 0,1:
    for z in 0,1:
      for w in 0,1:
        #F = not(x and y) and (y or z) or not(w)
        if F == 0:
          print(y,w,x,z,F)
```
## 2 задание
```python
Результат работы N МЕНЬШЕ 98
97 -> 1100001
98 -> 1100010
11000 -> 24
```

## 3 задание
```python
for s in range(10000):
    res = s

# КОД

    if n == #ОТВЕТ:
        print(res)
```

## 4 задание
```python
# Мак. количество цветов в палитре = N
Палитра равна: i = I / k = (Объём файла КБ переводим в биты) / (разрешение) = i
N = 2^i ; 
```

## 5 задание
```python
import itertools
count = 0
for x in itertools.product('ИГРА', repeat=4):
  count += 1
  print(count, ''.join(x))
```

## 6 задание
```python
Создать 2 ячейки
=СРЗНАЧ(B2:Y92) найдём среднее арифметическое значение всех измерений
=МАКС(B2:Y92) Для поиска максимального значения температуры воспользуемся формулой
Посчитать их разность
```

## 7 задание
НЕ СМЕШИТЕ МЕНЯ :)

## 8 задание
<img src="https://i.ibb.co/yX9XKSr/image.png" width="80%"/>

## 9 задание
```python
s = '3' * 250
while ('3333' in s) or ('7777' in s):
  if '3333' in s:
    s = s.replace('3333', '7', 1)
  else:
    s = s.replace('777', '3', 1)
print(s)
```

## 10 задание
```python
value = 64 ** 9 + 8 ** 25 - 9
sys = 8
result = ''
while value != 0:
  result = str(value % sys) + result
  value = value // sys
print(result.count('7'))
```

## 11 задание
```python
for A in range(1,500):
    OK = 1
    for x in range(1,1000):
        OK *= ((x % 40 == 0) or (x % 64 == 0))<=(x % A== 0)
    if OK:
        print( A )
```

## 12 задание
```python
# код последовательности
```

## 13 задание
```python
for x in range(1000):
    res = x

#КОД

    if L == #ОТВЕТ and M == #ОТВЕТ:
        print(res)
```