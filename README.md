# АНАЛИЗ ДАННЫХ И ИСКУССТВЕННЫЙ ИНТЕЛЛЕКТ [in GameDev]
Отчет по лабораторной работе #4 выполнил(а):
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
1)OR 8 эпох
Эпохи:
![image](https://user-images.githubusercontent.com/101055411/205239446-b0f77f60-c517-437a-9090-185111fee794.png)
![image](https://user-images.githubusercontent.com/101055411/205239493-b125f403-1721-472f-a6af-5d29401a8c79.png)
![image](https://user-images.githubusercontent.com/101055411/205239524-af0e4a51-1df0-416f-9798-0ec9402343a5.png)
![image](https://user-images.githubusercontent.com/101055411/205239550-293dfbd6-1d30-49ec-ac40-178af958cb0f.png)
Тесты:
![image](https://user-images.githubusercontent.com/101055411/205239563-c6c9cea0-5059-4ec6-bbea-ec0459ea5d7b.png)
Как видно, для OR вполне хватит 4 эпох, для того, чтобы обучиться. За первые 4-е эпохи Perceptron обучался на разных числовых значениях,
но когда обучился на 4-й эпохе, числа  пошли одинаковыми.
2)AND 8 эпох
Эпохи:
![image](https://user-images.githubusercontent.com/101055411/205240024-714b4f9b-81a6-4682-82c6-de8d30aacfc0.png)
![image](https://user-images.githubusercontent.com/101055411/205240074-9c538c5e-980d-49f8-bf43-1cd8dd14b778.png)
![image](https://user-images.githubusercontent.com/101055411/205240094-0964a466-81c5-42f1-ac6f-3f0c12161497.png)
![image](https://user-images.githubusercontent.com/101055411/205240121-d2a689a2-9bf9-4ec2-94f3-1624f76236fb.png)
Тесты:
![image](https://user-images.githubusercontent.com/101055411/205240151-953b299d-50cb-4388-a500-e717922b5cd7.png)
Для AND понадобилось больше эпох,чем для OR, ему понадобилось 7 эпох.
3)NAND 8 эпох
Эпохи:
![image](https://user-images.githubusercontent.com/101055411/205241284-0a053b93-e4d9-4c4e-ae46-17e1c2dee423.png)
![image](https://user-images.githubusercontent.com/101055411/205241326-9da7fa2d-800f-4116-ae70-87412aa5237c.png)
![image](https://user-images.githubusercontent.com/101055411/205241363-1d99b08d-cb6e-4de7-ab06-3a657b16f0ea.png)
![image](https://user-images.githubusercontent.com/101055411/205241407-e7187930-2a51-4220-b81e-400e1daf87fe.png)
Тесты:
![image](https://user-images.githubusercontent.com/101055411/205241462-945f8fc6-5ddc-4670-bad1-8ab46508442c.png)
Для NAND понадобилось 5 эпох.
4)XOR 8 эпох
Эпохи:
![image](https://user-images.githubusercontent.com/101055411/205242747-f91b5191-2103-4b8a-8a98-ce4560fcc5d7.png)
![image](https://user-images.githubusercontent.com/101055411/205242775-22f6b57c-3663-43fe-bfcd-92b3d4a8028d.png)
![image](https://user-images.githubusercontent.com/101055411/205242807-bf51bd95-9aa4-4f0f-9705-5bf265bd3892.png)
![image](https://user-images.githubusercontent.com/101055411/205242836-7c85b493-3181-456b-b56d-9093725f29f3.png)
Тесты:
![image](https://user-images.githubusercontent.com/101055411/205242886-33d9ef9f-6328-49e4-b9cc-fd40331c34ce.png)
Как видно, для XOR не хватает 8 эпох для обучения, поэтому нужно поднимать эпохи.
4.1)Для XOR 16 эпох не хватает
4.2)Для XOR 32 эпох не хватает


## Задание 2



## Задание 3



## Выводы



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
