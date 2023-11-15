# АНАЛИЗ ДАННЫХ И ИСКУССТВЕННЫЙ ИНТЕЛЛЕКТ [in GameDev]
Отчет по лабораторной работе #2 выполнил:
- Утев Денис Сергеевич
- РИ220944
Отметка о выполнении заданий:

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

![Build Status](https://github.com/denisUtev/URFU_AD/actions/workflows/build.yml/badge.svg)

## Цель работы
Выполнить все задания из воркшопа2.

## Задание 1
Ход работы:
- Выбрать одну из компьютерных игр, привезти скриншот её геймплея и краткое описание концепта игры. 
- Выбрать одну из игровых переменных в игре, описать её роль в игре, условия изменения / появления и диапазон допустимых значений. 
- Построить схему экономической модели в игре и указать место выбранного ресурса в ней.


```py

print("Hello World")

```

[Ссылка на файл с кодом в репозитории](1-Anaconda/HelloWorld.ipynb)


## Задание 2
Ход работы:
- Написать программу Hello World на C# с запуском на Unity. 

[Ссылка на скрин в Unity в репозитории](helloWorldUnity.png)

```C#
using System.Collections;
using System.Collections.Generic;
using UnityEngine;

public class Destroy : MonoBehaviour
{
    public GameObject obj;
    // Start is called before the first frame update
    void Start()
    {
        
    }

    // Update is called once per frame
    void Update()
    {
        if (Input.GetKeyUp(KeyCode.Space)) {
            Destroy(obj);
        }
    }
}
```


## Задание 3
Ход работы: 
- Оформить отчет в виде документации на github (markdown-разметка).

Готово!

## Выводы

Я выполнил задания воркшопа1, научился печатать в консоль "hello world" на питоне, а также в Unity.

| Plugin | README |
| ------ | ------ |
| Dropbox | [plugins/dropbox/README.md][PlDb] |
| GitHub | [plugins/github/README.md][PlGh] |
| Google Drive | [plugins/googledrive/README.md][PlGd] |
| OneDrive | [plugins/onedrive/README.md][PlOd] |
| Medium | [plugins/medium/README.md][PlMe] |
| Google Analytics | [plugins/googleanalytics/README.md][PlGa] |

## Powered by

**UTEV DENIS**
