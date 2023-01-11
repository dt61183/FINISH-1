**Задача**:

Написать программу, которая из имеющегося массива строк формирует новый массив из строк, длина которых меньше, либо равна 3 символам. Первоначальный массив можно ввести с клавиатуры, либо задать на старте выполнения алгоритма. При решении не рекомендуется пользоваться коллекциями, лучше обойтись исключительно массивами.

**Пример**:

[“Hello”, “2”, “world”, “:-)”] → [“2”, “:-)”]
[“1234”, “1567”, “-2”, “computer science”] → [“-2”]
[“Russia”, “Denmark”, “Kazan”] → []

**Решение**:

1. Создать массив с произвольным количеством элементов.
2. Напечатать каждый элемент массива.
3. Перебирать все элементы массива на предмет соответствия условию - длина элемента массива меньше или равна 3.
4. Если условие выполнено, вывести элмент массива на печать. Если условие не выполнено, ничего не делать.
5. Как только будут проверены все элементы массива, проверку прекратить.
