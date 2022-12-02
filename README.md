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
MLAgents

## Задание 1
1)Так как у меня другая версия, пришлось снова устанавливать пакеты

![image](https://user-images.githubusercontent.com/101055411/205290268-55abacd8-05a0-44e6-9621-bb0f3c99712f.png)

2)Создал втртуальное пространство

![image](https://user-images.githubusercontent.com/101055411/205290533-ae533f69-dbc5-434b-b138-5d0b21c02730.png)

3)Активировал пространство

![image](https://user-images.githubusercontent.com/101055411/205290709-116bec05-6405-46ac-b035-5f7a2c69bbab.png)

4)Установил пакеты, как в третей лабораторной работе

![image](https://user-images.githubusercontent.com/101055411/205290815-5301d865-dd35-43aa-97ba-e65d9077db50.png)
![image](https://user-images.githubusercontent.com/101055411/205290906-c3108db3-a600-4ecc-a315-57c1a2e841c6.png)

5)Зашёл в папку к файлу Economic.yaml

![image](https://user-images.githubusercontent.com/101055411/205291009-32793649-3e3f-4b5b-8d9b-5d9c2152e9be.png)

6)Сразу начал обучение на 12 префабов

![image](https://user-images.githubusercontent.com/101055411/205291354-b810a3cb-efb1-4c14-810f-544960118145.png)
![image](https://user-images.githubusercontent.com/101055411/205291177-89387da4-9f7d-4eb6-8f1b-2245306805ea.png)
![image](https://user-images.githubusercontent.com/101055411/205291256-ff85966a-78e2-4446-93c2-ecf4ce7fb563.png)

7)Установил Tensorflow

![image](https://user-images.githubusercontent.com/101055411/205291494-c9e6c956-6115-4b94-a398-ce7accb92c9e.png)
![image](https://user-images.githubusercontent.com/101055411/205291534-6c1f687b-740e-434a-9881-1bcc8d1c1cfe.png)

8)Запустил TensorBoard

![image](https://user-images.githubusercontent.com/101055411/205291593-1614c128-8ebe-43b7-a292-f13f7df51328.png)


9)Зашёл на сайт и увидел графики

![image](https://user-images.githubusercontent.com/101055411/205291717-b0086e78-3920-49f6-9585-6aaff58005d6.png)

10)Меняю параметры в Economic.yaml

а)Изменил  num_epoch с 3-х на 5

![image](https://user-images.githubusercontent.com/101055411/205292492-00901196-055e-4963-bc5b-cda0f2babf46.png)

Эта штучка - количество эпох.

б)Изменил lambd с 0.95 на 0.6

![image](https://user-images.githubusercontent.com/101055411/205293013-55694408-0ba3-4880-9606-b68e6367cf99.png)

Эта штучка нужна для расчёта общей оценки преимущества 'GAE'.

в)Изменил epsilon с 0.2 на 0.9

![image](https://user-images.githubusercontent.com/101055411/205293428-ed78d886-e496-401e-8e02-cf0df80a302f.png)

Эта штучка нужна для расчёта скорости развития политики, пока идёт обучение.



## Задание 2
Value loss - это разница между ожиданием алгоритмом обучения значения состояния и эмпирически наблюдаемым значением этого состояния.
Policy Loss - это средняя величина, которая отвечает за изменение процесса принятия решений.
Episode Length - показывает cреднюю длительность каждой эпохи для всех агентов в данной среде.
Cumulative reward - среднее вознаграждение в эпоху для всех агентов.


## Выводы
Могу подвести итоги. Я снова поигрался с консолью разработчика, как в 3-й лабораторной работе, снова подабавлял MLAgents и поскачивал разные ресурсы и пакеты. Проанализировал изменения на графиках, при изменении переменных в файле Economic.yaml.


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
