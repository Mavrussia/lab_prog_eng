# Тема 7. Работа с файлами (ввод, вывод)
Отчет по Теме #7 выполнил(а):
- Мордиков Артем Владимирович
- ПИЭ-22-1

| Задание | Лаб_раб | Сам_раб |
| ------ | ------ | ------ |
| Задание 1 | + | + |
| Задание 2 | + | + |
| Задание 3 | + | + |
| Задание 4 | + | + |
| Задание 5 | + | + |
| Задание 6 | + | 
| Задание 7 | + | 
| Задание 8 | + | 
| Задание 9 | + | 
| Задание 10 |+ |

знак "+" - задание выполнено; знак "-" - задание не выполнено;

Работу проверили:
- к.э.н., доцент Панов М.А.

## Лабораторная работа №1

### Код
```python

```

### Результат.

## Лабораторная работа №2

### Код
```python

```

### Результат.

## Лабораторная работа №3

### Код
```python

```

### Результат.

## Лабораторная работа №4

### Код
```python

```

### Результат.

## Лабораторная работа №5

### Код
```python

```

### Результат.

## Лабораторная работа №6

### Код
```python

```

### Результат.

## Лабораторная работа №7

### Код
```python

```

### Результат.

## Лабораторная работа №8

### Код
```python

```

### Результат.

## Лабораторная работа №9

### Код
```python

```

### Результат.

## Лабораторная работа №10

### Код
```python

```

### Результат.


## Самостоятельная работа №1
### Найдите в интернете любую статью (объем статьи не менее 200 слов), скопируйте ее содержимое в файл и напишите программу, которая считает количество слов в текстовом файле и определит самое часто встречающееся слово. Результатом выполнения задачи будет: скриншот файла со статьей, листинг кода, и вывод в консоль, в котором будет указана вся необходимая информация.

### Код
```python
from collections import Counter
import string

with open('statia.txt', 'r', encoding='utf-8') as file:
    text = file.read()

translator = str.maketrans('', '', string.punctuation)
clean_text = text.translate(translator).lower()

words = clean_text.split()

if words:
    word_count = len(words)
    word_frequencies = Counter(words)
    most_common_word, most_common_count = word_frequencies.most_common(1)[0]

    print(f"Общее количество слов в статье: {word_count}")
    print(f"Самое часто встречающееся слово: '{most_common_word}', встречается {most_common_count} раз(а)")
else:
    print("Файл пустой или не содержит слов.")

```

### Результат.

### Вывод


## Самостоятельная работа №2

### Код
```python

```

### Результат.

### Вывод


## Самостоятельная работа №3

### Код
```python

```

### Результат.

### Вывод


## Самостоятельная работа №4

### Код
```python

```

### Результат.

### Вывод


## Самостоятельная работа №5

### Код
```python

```

### Результат.

### Вывод


### Общий вывод
