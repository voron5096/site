## 1 задание
```python
print('y w x z')
for x in 0,1:
  for y in 0,1:
    for z in 0,1:
      for w in 0,1:
        F = not(x and y) and (y or z) or not(w)
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
    n = 1
    while s < 45:
        s = s + 6
        n = n * 4
    if n == 256:
        print(res)
```

## 4 задание
```python
Палитра равна: i = I / k = (145 * 1024 * 8) / 512 * 265 = 8,7
N = 2^8 ; i = 8
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
```python
26 + 10 + 8 = 44 = 64 (в большую сторону)
64 = 2^i
i = 6 (в большую сторону)
11 * 6 = 66 бит
72 / 8 = 9 байт
30 - 9 = 21 байт
1560 / 52 = 30
```

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
Мейби через формулу?

## 12 задание
Мейби через python

## 13 задание
```python
for x in range(70):
    res = x
    L = 0
    M = 0
    while x > 0:
        M = M + 2
        if x % 8 != 0:
            L = L + 1
        x = x // 8
    if L == 2 and M == 6:
        print(res)
```