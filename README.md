# Домашнее задание к занятию «Testability, автотесты, введение в ООП: объекты и методы»

## Задание 1. Мили — модернизация (обязательное к выполнению) <a href="https://github.com/RavenRVS/QAI_HW3_T1/tree/master/src">(моё решение) </a>

Вы уже научились создавать классы и методы. Поэтому вам необходимо модернизировать [приложение для расчёта миль](./PRIMITIVES.md). Теперь сама логика расчёта будет находиться в специально выделенном классе сервиса, а в Main мы будем лишь создавать объект этого сервиса и вызывать его метод, передавая аргументами все необходимые данные для расчёта. Получив от вызова метода рассчитанный результат, мы выведем его на экран.

#### Этапы выполнения
1. Создайте класс `BonusMilesService` (`File -> New -> Java Class`, вводите название и нажимаете `Enter`).
1. Определите в нём метод `calculate`, который:
    1. принимает на вход один параметр: `cost` типа `int`;
    1. анализируя значение переданного параметра, возвращает рассчитанное количество миль (тип — `int`).

Убедитесь, что выводимое в консоль значение соответствует результатам предыдущей версии приложения.

#### Результат
На проверку отправьте ссылку на ваш публичный репозиторий GitHub с решением.

## Задание 2*. Индекс массы тела (необязательная задача) <a href="https://github.com/RavenRVS/QAI_HW3_T2/tree/master/src">(моё решение) </a>

Вы решили написать сервис, который рассчитывает индекс массы тела (body mass index).

#### Этапы выполнения
1. Самостоятельно собрать информацию о том, какие входные данные нужны для расчёта, вы же умеете гуглить 😉
1. Создать класс `BmiService` с методом `calculate`. Помните, что вы считаете индекс, а не выдаёте диагноз.
1. Продемонстрировать в `Main` по аналогии с первой задачей:
    1. создание объекта,
    1. вызов метода `calculate`,
    1. печать в консоль результата,

#### Результат
На проверку отправьте ссылку на ваш публичный репозиторий GitHub с решением.

## Задание 3*. Кредитный калькулятор (необязательная задача повышенной сложности) <a href="https://github.com/RavenRVS/QAI_HW3_T3/tree/master/src">(моё решение) </a>

Вам поручили написать кредитный калькулятор, который считает как на сайте. Но формулы, естественно, не дали.

Вам нужно провести небольшой анализ и написать свой `CreditPaymentService`, который умеет рассчитывать ежемесячный платёж (см. аннуитетный платёж).

Параметры, их количество, типы, а также формулу вам необходимо определить исходя из скриншотов ниже.

Обратите внимание: на тех же данных ваш сервис должен считать так же.

Чтобы это продемонстрировать, в `Main` создайте объект и три раза вызовите его метод `calculate`. Результаты каждого вызова выводите в консоль.

Скриншоты для решения задачи. Важно: это не реальный сервис.

![image](https://user-images.githubusercontent.com/53707586/145564347-174ef746-013e-4793-bda1-79d81ac18e65.png)
![image](https://user-images.githubusercontent.com/53707586/145564368-0c1aaa9c-563b-4177-9ad6-a9f9adef8f92.png)
![image](https://user-images.githubusercontent.com/53707586/145564380-5140f2ab-312c-46c1-b423-1e5c209617b5.png)

#### Результат
На проверку отправьте ссылку на ваш публичный репозиторий GitHub с решением.

Каждое задание выполняйте в отдельном репозитории.
