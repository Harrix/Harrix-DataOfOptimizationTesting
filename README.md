HarrixDataOfOptimizationTesting
===============================

Версия 1.40

Сырые данные о тестировании алгоритмах оптимизации первого порядка в формате Harrix Optimization Testing.

https://github.com/Harrix/HarrixDataOfOptimizationTesting

Данные распространяются по лицензии [Apache License, Version 2.0](../master/LICENSE.txt).

Описание формата Harrix Optimization Testing 1.0 вы найдете тут:

https://github.com/Harrix/HarrixFileFormats

Для формата Harrix Optimization Testing 1.0 есть класс HarrixClass_DataOfHarrixOptimizationTesting для чтения и анализа данных:

https://github.com/Harrix/HarrixClass_DataOfHarrixOptimizationTesting

Всё множество исследованных алгоритмов оптимизации можно найти тут.

https://github.com/Harrix/HarrixOptimizationAlgorithms

Всё множество тестовых функций, по которым производится тестирования, можно найти тут.

https://github.com/Harrix/HarrixTestFunctions

Помните, что в одном xml файле находятся данные тестирования ОДНОГО алгоритма оптимизации на ОДНОЙ тестовой функции при ОДИНАКОВЫХ условиях, но рассматриваются ВСЕВОЗМОЖНЫЕ варианты настроек алгоритма.

Про структуру проекта
---------------------

Все данные располагаются в папке [**_Data**](../master/_Data).

В этой папке идут папки, где алгоритмы оптимизации рассортированы по типам решаемых задач:

 - [Алгоритмы бинарной оптимизации](../master/_Data/Алгоритмы бинарной оптимизации);
 - [Алгоритмы вещественной оптимизации](../master/_Data/Алгоритмы вещественной оптимизации).
 
В каждой папке идут папки по названиям алгоритмов оптимизации (описание смотреть тут: https://github.com/Harrix/HarrixOptimizationAlgorithms). Отправной точкой для исследований являются данные для [стандартного генетического алгоритма](https://github.com/Harrix/Standard-Genetic-Algorithm). 

Поэтому первой папкой в папке [Алгоритмы бинарной оптимизации](../master/_Data/Алгоритмы бинарной оптимизации) является папка [_MHL_StandartBinaryGeneticAlgorithm](../master/_Data/Алгоритмы бинарной оптимизации/_MHL_StandartBinaryGeneticAlgorithm) - данные исследования стандартного генетического алгоритма на бинарных строках. Второй папкой идет папка [_MHL_StandartBinaryGeneticAlgorithm - Повторные исследования](../master/_Data/Алгоритмы бинарной оптимизации/_MHL_StandartBinaryGeneticAlgorithm - Повторные исследования) - для проверки стабильности работы алгоритма.

Аналогично первой папкой в папке [Алгоритмы вещественной оптимизации](../master/_Data/Алгоритмы вещественной оптимизации) является папка [_MHL_StandartRealGeneticAlgorithm](../master/_Data/Алгоритмы вещественной оптимизации/_MHL_StandartRealGeneticAlgorithm) - данные исследования стандартного генетического алгоритма на вещественных строках. Второй папкой идет папка [_MHL_StandartRealGeneticAlgorithm - Повторные исследования](../master/_Data/Алгоритмы вещественной оптимизации/_MHL_StandartRealGeneticAlgorithm - Повторные исследования) - для проверки стабильности работы алгоритма.

Далее идут папки других алгоритмов оптимизации. В каждой из папок находятся файлы формата Harrix Optimization Testing, в которых находятся данные о тестировании алгоритмов на тестовых функциях.

В корневой папке располагается файл **Список проведенных исследований.xlsx** в котором приводится сводка наличия проведенных исследований на тестовых функциях.

Скриншоты
-------------------------------

![alt text](../master/imagesforgithub/example1.png "Пример XML файла")

![alt text](../master/imagesforgithub/example2.png "Пример анализа файла XML")

История проекта
---------------

Подробный список изменений в файле [CHANGELOG.md](../master/CHANGELOG.md).

Контакты
--------

Автор: Сергиенко Антон Борисович.

С автором можно связаться по адресу sergienkoanton@mail.ru или  http://vk.com/harrix.

Сайт автора, где публикуются последние новости: http://blog.harrix.org, а проекты располагаются по адресу: http://harrix.org.