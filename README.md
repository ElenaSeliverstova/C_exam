**Задача**
Написать программу, которая из имеющегося массива строк формирует массив из строк, длина которых меньше либо равна 3 символа. Первоначальный массив можно ввести с клавиатуры, либо задать на старте выполнения алгоритма. При решении не рекомендуется пользоваться коллекциями, лучше обойтись исключительно массивами.

**Алгоритм решения**
1. Объявить 2 массива: первичный и вторичный, который будет показывать отсеянные элементы на основании условий
2. Создать метод, который будет проверять каждый из элементов i массива 1 на условие if длина элемента <= 3, тогда элемент заносим в массив 2
3. Объявить переменную count, которая будет поочередно проверять элементы, каждый раз увеличивая длину нового массива на 1
4. Добавить метод для вывода обновленного массива

