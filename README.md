HarrixDataOfOptimizationTesting
===============================

Версия 2.1

Сырые данные о тестировании алгоритмов оптимизации первого порядка в формате Harrix Optimization Testing.

[https://github.com/Harrix/HarrixDataOfOptimizationTesting](https://github.com/Harrix/HarrixDataOfOptimizationTesting)

Данные распространяются по лицензии [MIT](https://github.com/Harrix/HarrixDataOfOptimizationTesting/blob/master/LICENSE).

Описание формата Harrix Optimization Testing 1.0 вы найдете тут:

[https://github.com/Harrix/HarrixFileFormats](https://github.com/Harrix/HarrixFileFormats)

Для формата Harrix Optimization Testing 1.0 есть класс HarrixClass_DataOfHarrixOptimizationTesting для чтения и анализа данных:

[https://github.com/Harrix/HarrixClass_DataOfHarrixOptimizationTesting](https://github.com/Harrix/HarrixClass_DataOfHarrixOptimizationTesting)

Всё множество исследованных алгоритмов оптимизации можно найти тут.

[https://github.com/Harrix/HarrixOptimizationAlgorithms](https://github.com/Harrix/HarrixOptimizationAlgorithms)

Всё множество тестовых функций, по которым производится тестирования, можно найти тут.

[https://github.com/Harrix/HarrixTestFunctions](https://github.com/Harrix/HarrixTestFunctions)

Помните, что в одном XML файле находятся данные тестирования ОДНОГО алгоритма оптимизации на ОДНОЙ тестовой функции при ОДИНАКОВЫХ условиях, но рассматриваются ВСЕВОЗМОЖНЫЕ варианты настроек алгоритма.

Установка
---------

Прочитать подробно об установке можно тут [http://blog.harrix.org/?p=1245](http://blog.harrix.org/?p=1245).

Про структуру проекта
---------------------

Все данные располагаются в папке [**\_Data**](https://github.com/Harrix/HarrixDataOfOptimizationTesting/blob/master/_Data).

В этой папке идут папки, где алгоритмы оптимизации рассортированы по типам решаемых задач:

 - [Алгоритмы бинарной оптимизации](https://github.com/Harrix/HarrixDataOfOptimizationTesting/blob/master/_Data/Алгоритмы%20бинарной%20оптимизации);
 - [Алгоритмы вещественной оптимизации](https://github.com/Harrix/HarrixDataOfOptimizationTesting/blob/master/_Data/Алгоритмы%20вещественной%20оптимизации).
 
В каждой папке идут папки по названиям алгоритмов оптимизации (описание смотреть тут: [https://github.com/Harrix/HarrixOptimizationAlgorithms](https://github.com/Harrix/HarrixOptimizationAlgorithms)). Отправной точкой для исследований являются данные для [стандартного генетического алгоритма](https://github.com/Harrix/Standard-Genetic-Algorithm). 

Поэтому первой папкой в папке [Алгоритмы бинарной оптимизации](https://github.com/Harrix/HarrixDataOfOptimizationTesting/blob/master/_Data/Алгоритмы%20бинарной%20оптимизации) является папка [\_HML\_StandartBinaryGeneticAlgorithm](https://github.com/Harrix/HarrixDataOfOptimizationTesting/blob/master/_Data/Алгоритмы%20бинарной%20оптимизации/_HML_StandartBinaryGeneticAlgorithm) - данные исследования стандартного генетического алгоритма на бинарных строках. Второй папкой идет папка [\_HML\_StandartBinaryGeneticAlgorithm - Повторные исследования](https://github.com/Harrix/HarrixDataOfOptimizationTesting/blob/master/_Data/Алгоритмы%20бинарной%20оптимизации/_HML_StandartBinaryGeneticAlgorithm%20-%20Повторные%20исследования) - для проверки стабильности работы алгоритма.

Аналогично первой папкой в папке [Алгоритмы вещественной оптимизации](https://github.com/Harrix/HarrixDataOfOptimizationTesting/blob/master/_Data/Алгоритмы%20вещественной%20оптимизации) является папка [\_HML\_StandartRealGeneticAlgorithm](https://github.com/Harrix/HarrixDataOfOptimizationTesting/blob/master/_Data/Алгоритмы%20вещественной%20оптимизации/_HML_StandartRealGeneticAlgorithm) - данные исследования стандартного генетического алгоритма на вещественных строках. Второй папкой идет папка [\_HML\_StandartRealGeneticAlgorithm - Повторные исследования](https://github.com/Harrix/HarrixDataOfOptimizationTesting/blob/master/_Data/Алгоритмы%20вещественной%20оптимизации/_HML_StandartRealGeneticAlgorithm%20-%20Повторные%20исследования) - для проверки стабильности работы алгоритма.

Далее идут папки других алгоритмов оптимизации. В каждой из папок находятся файлы формата Harrix Optimization Testing, в которых находятся данные о тестировании алгоритмов на тестовых функциях.

В корневой папке располагается файл **ListOfExperiments.xlsx** в котором приводится сводка наличия проведенных исследований на тестовых функциях.

Скриншоты
-------------------------------

![alt text](https://raw.github.com/Harrix/HarrixDataOfOptimizationTesting/master/imagesforgithub/example1.png "Пример XML файла")

![alt text](https://raw.github.com/Harrix/HarrixDataOfOptimizationTesting/master/imagesforgithub/example2.png "Пример анализа файла XML")

Использованные технологии
-------------------------

- [XML](http://ru.wikipedia.org/wiki/XML).
- [Harrix Optimization Testing](https://github.com/Harrix/HarrixFileFormats).

История проекта
---------------

Подробный список изменений в файле [CHANGELOG.md](https://github.com/Harrix/HarrixDataOfOptimizationTesting/blob/master/CHANGELOG.md).

Контакты
--------

Автор: Сергиенко Антон Борисович.

С автором можно связаться по адресу [sergienkoanton@mail.ru](mailto:sergienkoanton@mail.ru) или  [http://vk.com/harrix](http://vk.com/harrix).

Сайт автора, где публикуются последние новости: [http://blog.harrix.org](http://blog.harrix.org), а проекты располагаются по адресу: [http://harrix.org](http://harrix.org).