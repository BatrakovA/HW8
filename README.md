# Homework8
## todo

### Домашнее задание к лекции "Регулярные выражения"

***Задание 1***

Напишите функцию, которая принимает на вход строку и проверяет является ли она валидным транспортным номером (1 буква, 3 цифры, 2 буквы, 2-3 цифры). Обратите внимание, что не все буквы кириллического алфавита используются в транспортных номерах.

Если номер валиден, то функция должна возвращать отдельно номер и регион.

Примеры работы программы:

car_id = 'А222BС96’
Результат: Номер А222BС валиден. Регион: 96

car_id = 'АБ22ВВ193’
Результат: Номер не валиден

***Задание 2***

Напишите функцию, которая будет удалять все последовательные повторы слов из заданной строки при помощи регулярных выражений.

Пример работы программы:

some_string = ‘Напишите функцию функцию, которая будет будет будет будет удалять все все все все последовательные повторы слов из из из из заданной строки строки при помощи регулярных выражений’

Результат: Напишите функцию, которая будет удалять все последовательные повторы слов из заданной строки при помощи регулярных выражений.

***Задание 3***

Напишите функцию, которая будет возвращать акроним по переданной в нее строке со словами.

Примеры работы программы:

some_words = 'Информационные технологии’
Результат: ИТ

some_words = 'Near Field Communication’
Результат: NFC

***Задание 4***

Напишите функцию, которая будет принимать на вход список email-адресов и выводить их распределение по доменным зонам.

Пример работы программы:

emails = [‘test@gmail.com, xyz@test.in, test@ya.ru, xyz@mail.ru, xyz@ya.ru’, xyz@gmail.com]

Результат:

gmail.com: 2
test.in: 1
ya.ru: 2
mail.ru: 1

***Задание 5 (необязательное)***

Напишите функцию, которая будет подсчитывать сколько слов начинается на гласные, а сколько на согласные буквы в тексте (текст может быть написан как с использованием букв кириллицы, так и латиницы).

Пример работы программы:

some_text = ‘Эталонной реализацией Python является интерпретатор CPython, поддерживающий большинство активно используемых платформ. Он распространяется под свободной лицензией Python Software Foundation License, позволяющей использовать его без ограничений в любых приложениях, включая проприетарные.’

Результат:

Слов на гласные буквы: 9
Слов на согласные буквы: 21

***Задание 6 (необязательное)***

Напишите функцию, которая будет проверять номер сотового телефона на валидность, если он валиден, то переводить его в формат:
+7-xxx-xxx-xx-xx
Постарайтесь предусмотреть как можно больше адекватных форматов изначального ввода номера. Примеры работы программы:

phone = '+7 955 555-55-55’
Результат: +7-950-555-55-55

phone = '8(955)555-55-55’
Результат: +7-950-555-55-55

phone = '+7 955 555 55 55’
Результат: +7-950-555-55-55

phone = '7(955) 555-55-55’
Результат: +7-950-555-55-55

phone = '423-555-55-5555’
Результат: Номер не валиден

phone = '123-456-789’
Результат: Номер не валиден