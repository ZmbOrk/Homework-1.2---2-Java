# Отчёт о тестировании Precision

## Краткое описание

16.03.21 - 16.03.21 было проведено функциональное тестирование приложения Main.java.

На тестирование затрачено: 1h

Тестирование производилось в следующем окружении:
* Win 10, 64x
* Java 11
* IDEA
* Main.java

В результате тестирования выявлены следующие дефекты:
* [#1 Неверная сумма в подсчете бонусов из-за некорректных типов данных в коде](https://github.com/ZmbOrk/Homework-1.2---2-Java/issues/1)

## Описание процесса тестирования

В качестве тестовых данных использовались данные из [Задача №2 - Precision](https://github.com/netology-code/javaqa-homeworks/tree/master/programming):
 
 Созданные переменные:
* double regularBonus = 0.3
* double specialBonus = 0.6
* double totalBonus = regularBonus + specialBonus

## Результат тестирования

 В результате тестирования было выявлено, что из-за неверного представления переменных в коде идет неверное сложение чисел. 
