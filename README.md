# АНАЛИЗ ДАННЫХ И ИСКУССТВЕННЫЙ ИНТЕЛЛЕКТ [in GameDev]
Отчет по лабораторной работе #1 выполнил(а):
- Зверев Артем Сергевич
- РИ210932
Отметка о выполнении заданий (заполняется студентом):

| Задание | Выполнение | Баллы |
| ------ | ------ | ------ |
| Задание 1 | * | 60 |
| Задание 2 | * | 20 |
| Задание 3 | * | 20 |

знак "*" - задание выполнено; знак "#" - задание не выполнено;

Работу проверили:
- к.т.н., доцент Денисов Д.В.
- к.э.н., доцент Панов М.А.
- ст. преп., Фадеев В.О.

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
Ознакомиться с основными операторами зыка Python на примере реализации линейной регрессии.

## Задание 1
### Выведен "Hello world!" на python и Unity 
![python(Hello world!).png](https://github.com/AmL3ar/UrFU-GameDev-/blob/main/python(Hello%20world!).png)
![unity(Hello world!).png](https://github.com/AmL3ar/UrFU-GameDev-/blob/main/unity(Hello%20world!).png)

## Задание 2
### Пошагово выполнить каждый пункт раздела "ход работы" с описанием и примерами реализации задач
Шаг первый: Мы использовали 2 библиотеки: numpy и matplotlib.pyplot
Дальше, написав данные для списков x и y,  мы создали массивы с помощью библиотеки numpy и передали в них значения списков.
После этого построили график, благодаря библиотеке matplotlib.pyplot - https://github.com/AmL3ar/UrFU-GameDev-/blob/main/шаг%201.png
Шаг второй: мы создали 4 функции: model; loss_function; optimize; iterare, каждая из которых выполняет свою обязанность.
model - определяет модель линейной регрессии a * x + b
loss_function - определяет среднеквадратичную ошибку
optimize - оптимизация, которая идёт по методу градиентного спуска для нахождения частных производных a и b
iterate - производит итерацию 
https://github.com/AmL3ar/UrFU-GameDev-/blob/main/шаг2.png
шаг третий: Проверяем разные итерации:
первая итерация - https://github.com/AmL3ar/UrFU-GameDev-/blob/main/1итерация.png
вторая итерация - https://github.com/AmL3ar/UrFU-GameDev-/blob/main/2итерация.png
третья итерация - https://github.com/AmL3ar/UrFU-GameDev-/blob/main/3итерация.png
четвертая итерация - https://github.com/AmL3ar/UrFU-GameDev-/blob/main/4итерация.png
пятая итерация - https://github.com/AmL3ar/UrFU-GameDev-/blob/main/5итерация.png
десятитысячная итерация - https://github.com/AmL3ar/UrFU-GameDev-


## Задание 3
### Должна ли величина loss стремиться к нулю при изменении исходных данных? Ответьте на вопрос, приведите пример выполнения кода, который подтверждает ваш ответ.
### Какова роль параметра Lr? Ответьте на вопрос, приведите пример выполнения кода, который подтверждает ваш ответ. В качестве эксперимента можете изменить значение параметра.
Lr - из графиков видно, что при уменьшении Lr будет изменение направления прямой, чем меньше, тем больше угол наклона у неё будет
https://github.com/AmL3ar/UrFU-GameDev-/blob/main/lr1.png
https://github.com/AmL3ar/UrFU-GameDev-/blob/main/lr2.png
loss стремится к нулю. При каждом увеличении итераций, она уменьшается, при 10000 итераций loss = 190... , при 1000000 loss = 182..., при 2000000 loss = 178...
https://github.com/AmL3ar/UrFU-GameDev-/blob/main/10000.png
https://github.com/AmL3ar/UrFU-GameDev-/blob/main/1000000.png
https://github.com/AmL3ar/UrFU-GameDev-/blob/main/2000000.png


## Выводы
Я узнал, как работают библиотеки numpy и matplotlib.pyplot. Рассмотрев код, улучшил свои навыки анализа программы. Научился создавать свой репозиторий GitHub. Впервые на Unity написал "Hello World!"


| Plugin | README |
| ------ | ------ |
| Dropbox | [plugins/dropbox/README.md][PlDb] |
| GitHub | [plugins/github/README.md][PlGh] |
| Google Drive | [plugins/googledrive/README.md][PlGd] |
| OneDrive | [plugins/onedrive/README.md][PlOd] |
| Medium | [plugins/medium/README.md][PlMe] |
| Google Analytics | [plugins/googleanalytics/README.md][PlGa] |

## Powered by

**BigDigital Team: Denisov | Fadeev | Panov**
