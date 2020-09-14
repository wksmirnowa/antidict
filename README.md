# Проект Antidict
HSE 2019-2020

Время еженедельного созвона – пятница 21:00 

## Описание проекта

Мы создаем базу морфологических структур, которые можно встретить в современном русскоязычном сегменте интернета и которые не распознаются крупными парсерами ГИКРЯ и mystem.
 
**Идея проекта**: изучение заимствований, экспрессивных форм и намеренных искажений.

**Что мы делаем**: классифицируем набор данных.

**Что мы хотим получить в итоге**: датасет, разбитый на классы.


## Над проектом работают 
**Студенты**: Алексей Доркин, Владислава Смирнова, Антон Вахранев

**Куратор**: Варвара Магомедова

[Техническое задание на проект](https://docs.google.com/document/d/1fpn72q8bKqhFnCaTmbqGZEtWS6WcXIP9WC1VpviAGEc/edit#)

[Координация работы по проекту](https://trello.com/b/XEnCTnHj/antidict)

## Цели и задачи проекта на 2019-2020 учебный год

### Цель 1 (академическая). 

Изучить:

– заимствования

– экспрессивные формы

– намеренные искажения

### Цель 2 (образовательная). 

Изучить разные библиотеки для обработки текста (mystem, fastText, pandas).

### Цель 3 (основная).

Создать датасет со словами, принадлежащими к трем интересующим нас классам.

## Технические задачи

### Задача 1

Определить формальные критерии, по которым мы будем разграничивать слова, относящиеся к разным категориям.

### Задача 2

Составить обучающую выборку и натренировать классификаторы находить слова из разных классов.

### Задача 3

Сравнить работу разных алгоритмов и применить лучшие для целевого множества слов, чтобы создать датасеты со словами наших целевых классов.

## Лингвистические задачи

### Задача 1

Изучить, какие разновидности англицизмов, эрративов и экспрессивных форм находятся в наших данных. 

### Задача 2

Определить систему формальных критериев, на основе которой мы создадим обучающую выборку для нахождения целевых классов слов. 

## Научная статья

[Научная статья](https://docs.google.com/document/d/1emjyoURAS04NAJ9B-wf-T4BE5FbthulvbPZq59v0igo/edit#), которую мы написали по итогу работы, – описание заимствований, экспрессивных форм и слов с искажениями, выявленных в данных, а также методов, использованных для их классификации.

## Датасеты
[Слова с искажениями](https://drive.google.com/file/d/103JsyDMN-n_P9DDe4zc-t4BkqZM6vAs7/view)
[Слова, классифицированные как англицизмы](https://raw.githubusercontent.com/wksmirnowa/antidict/master/Data/anglicisms.csv)
