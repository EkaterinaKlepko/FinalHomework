# Задача:
Написать программу, которая из имеющегося массива строк, формирует массив строк, длинна которых меньше либо равна 3 символа.

# Решение:
1. Задать массив строк произвольной длинны
2. Задать новый массив, в который будут складываться элементы первого массива, соответсвующие условиям задачи.
3. Создать фукцию, которая будет проверять длинну элементов массива.
    * создать переменную "count", равную нулю, с помощью которой необходимые элементы первого массива будут расставляться в новом массиве.
    * при помощи цикла "for" проверить все элементы первого массива на соответствие условиям задачи
    * подходящим элементам массива с помощью увеличения переменной "count" присваем индексы нового массива.
4. Создаем функцию для вывода нового массива.
    * Выводим новый массив с помощью цикла "for".
5. Вызываем созданные функции.