# python-ternar-circle-tasks
Python Задачи на тернарный оператор и циклы

## Задача 1
1. Перепишите этот пример, используя инструкцию if else так,
   чтобы результат был таким же, как сейчас.
2. Cделайте так, чтобы с помощью тернарного оператора можно было проверить длину строки.
   То есть, есть ли длина строки больше 79 символов, то вы печатаете в терминал текст: "String is long", иначе пишете  текст: "String is short".

## Задача 2

1. Создайте функцию dict_to_list, которая будет конвертировать словарь в список кортежей
2. Функция должна принимать словарь, а возвращать список (list)  кортежей, в каждом кортеже
   должны быть пары (key, value) из словаря
3. Если значение ключа - целое число, то его нужно умножить на 2 перед добавлением в кортеж.
   Это значит, что необходимо изменить значение некоторых ключей

## Задача 3

1. Создайте функцию filter_list, которая будет фильтровать список
2. У функции должно быть два параметра - список и тип значения 
(функция будет вызываться с двумя аргументами)
3. Функция должна вернуть новый список, в котором останутся только значения того типа, который был
передан в вызове функции вторым аргументом. То есть, задача функции в том, чтобы принять список со значениями разных типов и отфильтровать этот список, оставив в нём только те значения, которые имеют определённый тип, например, оставить только целые числа, либо же оставить только строки и вернуть результирующий список.
4. Функцию можно будет вызвать например так:
filter_list([35, True, 'abc', 10], int) и получить [35, 10]
