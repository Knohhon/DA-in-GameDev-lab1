# АНАЛИЗ ДАННЫХ И ИСКУССТВЕННЫЙ ИНТЕЛЛЕКТ [in GameDev]
Отчет по лабораторной работе #1 выполнил(а):
- Резов Дмитрий Олегович
- РИ210911

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
Ознакомиться с основными операторами языка Python на примере реализации линейной регрессии.

## Задание 1
Hello world на Unity:
![image](https://user-images.githubusercontent.com/112959757/192843596-f3011e16-18d7-4c6d-a37f-852900b28600.png)

Hello world на Python в Google Colab:
![image](https://user-images.githubusercontent.com/112959757/192843714-ab4b4aaf-2308-4e31-9370-64aebc8f857a.png)
![image](https://user-images.githubusercontent.com/112959757/192843743-ab7e1e90-a6e9-4579-992e-56329edda106.png)

## Задание 2
Пошаговое выполнение работы:
![1](https://user-images.githubusercontent.com/112959757/192844135-ee4f5bf8-25fb-48b5-ba21-b6a80306bb3a.png)
![2](https://user-images.githubusercontent.com/112959757/192844159-022528db-9cdf-40da-9184-93c5c8f9c98b.png)
![3](https://user-images.githubusercontent.com/112959757/192844180-0e7deb51-4ca7-4014-bff1-71bccd099225.png)
![4](https://user-images.githubusercontent.com/112959757/192844202-759ab8a4-6caf-43c1-b30b-6f3dc52624cf.png)
![5](https://user-images.githubusercontent.com/112959757/192844291-b17b2b06-610d-4884-a59d-b87b5d79b984.png)
![6](https://user-images.githubusercontent.com/112959757/192844319-c48c604d-1c49-490f-83df-627ac3785229.png)
![7](https://user-images.githubusercontent.com/112959757/192844338-dfbc0002-c961-4ba6-a5f8-21bb9180ae12.png)
![8](https://user-images.githubusercontent.com/112959757/192844372-c243db13-c4f8-4ba8-a339-6034c95054c9.png)

## Задание 3
### Должна ли величина loss стремиться к нулю при изменении исходных данных? Ответьте на вопрос, приведите пример выполнения кода, который подтверждает ваш ответ.
Ответ: Не всегда, при f(x) = (a*x[i] + b) -> y[i], loss -> 0, т.к сумма квадратичных ошибок -> 0.
![Example1](https://user-images.githubusercontent.com/112959757/192849171-0885938f-8b2e-4442-830a-5c0b427ce87c.png)
В коде я добавил несколько итераций, в ходе которых x[i] -> y[i].
Видно, что с каждой итерацией loss -> 0.
### Какова роль параметра Lr? Ответьте на вопрос, приведите пример выполнения кода, который подтверждает ваш ответ. В качестве эксперимента можете изменить значение параметра.
Ответ: Lr - альфа-коэффициент, необходимый чтобы избежать избыточной коррекции весов a, b.
![Example2](https://user-images.githubusercontent.com/112959757/192852690-29e0611c-4119-4f0d-be2e-b86b7b5b81a7.png)
Я увеличил Lr до 0.01 и уменьшил кол-во итераций до 100. Получилось расхождение.
## Выводы

В ходе лабораторной работы мы: 
1) Настроили Unity и VS Code.
2) Ознакомились с основными операторами языка Python на примере реализации линейной регрессии.
3) Рассмотрели некоторые тонкости реализации алгоритма линейной регрессии.

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
