# Анализ данных в разработке игр
Отчет по лабораторной работе #3 выполнил(а):
- Бабаев Тимур Ахмадалиевич
- РИ-220912
Отметка о выполнении заданий (заполняется студентом):

| Задание | Выполнение | Баллы |
| ------ | ------ | ------ |
| Задание 1 | * | - |
| Задание 2 | * | - |
| Задание 3 | * | - |

знак "*" - задание выполнено; знак "#" - задание не выполнено;

Работу проверили:
-

[![N|Solid](https://cldup.com/dTxpPi9lDf.thumb.png)](https://nodesource.com/products/nsolid)

[![Build Status](https://travis-ci.org/joemccann/dillinger.svg?branch=master)](https://travis-ci.org/joemccann/dillinger)

Структура отчета

- Данные о работе: название работы, фио, группа, выполненные задания.
- Цель работы.
- Задание 1.
- Код реализации выполнения задания. Визуализация результатов выполнения (если применимо).
- Задание 2.
- Код реализации выполнения задания. Визуализация результатов выполнения (если применимо).
- Задание 3.
- Код реализации выполнения задания. Визуализация результатов выполнения (если применимо).
- Выводы.
- ✨Magic ✨

## Цель работы
Познакомиться с программными средствами для создания системы машинного обучения и ее интеграции в Unity.

## Задание 1
### Найдите внутри C# скрипта “коэффициент корреляции ” и сделать выводы о том, как он влияет на обучение модели.
Долго пытался найти, что за коэффициент корреляции и для чего он нужен, и пришёл к тому, что в скрипте RollerAgent.cs есть одна интересная вещь - дистанция до цели.

Я думаю что в данном случае переменную distanceToTarget можно назвать коэффициентом корреляции, так как это единственный объект обеспечивающий связь агента с его целью. И награда агенту начисляется только, если он достиг цели, обозначенной этой переменной.

Влияет он на обучение модели самым прямым образом - если он будет слишком велик, то модель будет обучаться быстрее, но при этом допускать много ошибок. Если же его сделать слишком маленьким, то обучение будет очень долгим, но при этом модель будет точнее и соответственно будет допускать меньше ошибок.

![image](https://github.com/truefolder/AD_ingamedev_lab5/assets/89926388/9c233b5a-6bc5-49c3-ba48-d7a398b208ec)


## Задание 2
### Изменить параметры файла yaml-агента и определить какие параметры и как влияют на обучение модели. Привести описание не менее трех параметров.

## Задание 3
### Приведите примеры, для каких игровых задачи и ситуаций могут использоваться примеры 1 и 2 с ML-Agent’ом. В каких случаях проще использовать ML-агент, а не писать программную реализацию решения? 

## Выводы

## Powered by

**BigDigital Team: Denisov | Fadeev | Panov**
