# xUnit For 1C - Set of unit testing tools for 1C:Enterprise 8 platform

xUnit For 1C is a set of unit testing tools for 1C:Enterprise 8 platform (http://v8.1c.ru).

xUnit для 1С - набор инструментов для выполнения юнит-тестирования (модульного тестирования) в 1С:Предприятии 8.

[Посмотрите Wiki](https://github.com/xDrivenDevelopment/xUnitFor1C/wiki)

## Что к чему

* *UnitTestRunner.epf* - браузер и исполнитель тестов для обычного приложения 1С:Предприятия 8
* *TestRunner.js* - скрипт для Снегопата, позволяющий выполнять тесты прямо из конфигуратора
* *Тесты/* - каталог с примерами тестов и с тестами для самотестирования UnitTestRunner.epf (подпапка selftests)

### Возможности UnitTestRunner.epf

UnitTestRunner.epf почти полнофункционален - умеет загружать тесты из произвольно выбранного каталога и выполнять все загруженные тесты скопом.
По одному тесту пока запускать не умеет.

### Ограничения TestRunner.js

TestRunner.js пока находится в состоянии "proof of concept" и для практического применения бесполезен.
Имеют место быть следующие ограничения:

1. Работает только макрос "Выполнить все тесты", остальные макросы не работают.
2. Выполняются тесты из жестко прописанного каталога <Каталог Снегопата>\user\1CUnit\Тесты

В виду п. 2. содержимое репозитария надо разместить там, в ближайшее время планируется это неудобство устранить.

## Как помочь проекту

Мы рады любой помощи: 

1. Если вы занимаетесь разработкой на 1С:Преприятии 8 пробуйте писать и выполнять тесты при помощи 1CUnit, сообщайте нам об обнаруженных ошибках, пишите пожелания. Для управления сообщениями об ошибках и пожеланиями мы используем [баг-трекер GitHub'а](https://github.com/kuntashov/1CUnit/issues?sort=created&state=open).

2. Если у вас есть время разобраться в исходном коде, вы можете взять на себя реализацию одной из  [открытых задач](https://github.com/kuntashov/xUnitFor1C/issues?sort=created&state=open).

3. Если вы уже используете xUnit For 1C на практике, напишите об этом статью, например, на [Инфостарте](http://infostart.ru).
