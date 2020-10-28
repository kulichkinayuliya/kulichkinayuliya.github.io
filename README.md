## Отчет о лабораторных работах 
## Студент группы ИДБ-17-06 Куличкина Ю.О.

## Лабораторная работа №1

Предложение: Мастер рисует татуировку.
![none](https://github.com/kulichkinayuliya/kulichkinayuliya.github.io/blob/master/lab1/modeldiagram.png)

Полное предложение: Мастер должен нарисовать татуировку в соответствии с заказом, используя машинку и краску.

Диаграмма классов:

![none](https://github.com/kulichkinayuliya/kulichkinayuliya.github.io/blob/master/lab1/ClassDaigram.png)

Диаграмма прецедентов:

![none](https://github.com/kulichkinayuliya/kulichkinayuliya.github.io/blob/master/lab1/PrnDiagram.png)

## Лабораторная работа №2

На диаграмме изображен процесс рисования татуировки.

## Диаграмма IDF0:
![none](https://github.com/kulichkinayuliya/kulichkinayuliya.github.io/blob/master/lab2/IDF00.png)

## Подуровень IDF0 диаграммы:
![none](https://github.com/kulichkinayuliya/kulichkinayuliya.github.io/blob/master/lab2/IDF001.png)

## А1

Администратор получает на вход эскиз клиента и заказ. На выходе получается записанный в базу клиент.

## А2

Тату-мастер получает на вход согласованный заказ, эскиз заказчика и копировальные инструменты. На выходе получается согласованный перенос эскиза на кожу.

## А3

Тату-мастер получает на вход заказ, тату-машинку и краску. На выходе получается татуировка.

## DFD диаграмма:
![none](https://github.com/kulichkinayuliya/kulichkinayuliya.github.io/blob/master/lab2/dfd1.png)

Администратор получает обращение клиента, предоставляет ему список услуг, и, при положительном выборе клиента, добавляет его в базу данных.

## Диаграмма прецедентов:
![none](https://github.com/kulichkinayuliya/kulichkinayuliya.github.io/blob/master/lab2/diag.png)

## Лабораторная работа №3

## Диаграмма последовательности
[Текст](https://github.com/kulichkinayuliya/kulichkinayuliya.github.io/blob/master/lab3/diagposl.txt) и [Рисунок](https://github.com/kulichkinayuliya/kulichkinayuliya.github.io/blob/master/lab3/diagposl.png) диаграммы последовательности.

![none](https://github.com/kulichkinayuliya/kulichkinayuliya.github.io/blob/master/lab3/diagposl.png)

Администратор обращается к базе данных через веб приложение для добавление нового заказа ( с ФИО, описанием, номером телефона), а тату-мастер через интерфейс веб-приложения на своей строне принимает заказ.

## ER-диаграмма
[Текст](https://github.com/kulichkinayuliya/kulichkinayuliya.github.io/blob/master/lab3/er.txt) и [Рисунок](https://github.com/kulichkinayuliya/kulichkinayuliya.github.io/blob/master/lab3/er.png) диаграммы классов.

![none](https://github.com/kulichkinayuliya/kulichkinayuliya.github.io/blob/master/lab3/er.png)

Заказ - это запись в базе данных, которая относится к информационным потокам, и состоит из: ФИО, описания и номера телефона.
