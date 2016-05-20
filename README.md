#Тестовое задание на позицию ведущего разработчика ОРИТ

Необходимо написать консольное приложение, которое расчитывает сумму поставок с учетом валюты по определенному Поставщику.

##Пример поставщика:

|Код|Наименование|
|---|------------|
|1  |ИП Альфа    |
|2  |АО Бета     |

##Пример поставки:

|Код|Номер|Код Поставщика|Валюта|Сумма   |
|---|-----|--------------|------|--------|
|1  |П0001|1             |810   |40000   |
|2  |П0002|1             |840   |1200    |
|3  |П0003|1             |810   |1000    |
|3  |i1-1 |2             |810   |23000   |
|4  |i1-2 |2             |840   |890     |

##Алгоритм действий пользователя

* При старте программа должна вывести названия всех Поставщиков.
* Пользователь должен выбрать Поставщика с помощью ввода кода. 
* На выходе получаем строки с суммой поставок.

##Пример:

```
Поставщики:
1: ИП Альфа
2: АО Бета
Введите код поставщика: 1
Сумма поставок:
Кол-во: 2, Сумма в валюте 810: 41000
Кол-во: 1, Сумма в валюте 840: 1200
```

Во время выполнения задания Вы должны учитывать неправильный ввод,
возможность расширения (добавление Поставщиков, поставок, использование базы данных и т.п.). Использование unit-тестирования приветствуется.

Результатом выполнения является готовый проект c исходными кодами, который компилируется.
Вы можете использовать любые инструменты.
