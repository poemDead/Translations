Вы вероятно уже решили задачу [Minimum of Three](./min-of-three) - и она показалась лёгкой? Давайте теперь слегка изменим
условие, чтобы получилось более сложное упражнение.

Вновь будут даны тройки чисел, но теперь нужно выбрать среднее из них - т.е. то, которое останется если отбросить
наибольший и наименьший элементы. Такое число называется **медианой** (множества, массива и т.п.)

Не думайте что это всего лишь "очередное дурацкое упражнение" - выбор медианы является частью мощного и популярного
алгоритма быстрой сортировки (QuickSort) например.

**Входные данные** - первая строка содержит количество тестовых наборов чисел.  
Остальные строки содержат сами наборы (тройки) - по одной в каждой строке.  
**Ответ** должен содержать медианы этих троек, разделенные пробелами.

Пример:

    входные данные:
    3
    7 3 5
    15 20 40
    300 550 137
    
    ответ:
    5 20 300

**Замечание**: если ваша программа содержит кучу конструкций if-else-if-else, то вероятно вы делаете что-то не так.
Простое решение состоит не более чем из трёх ветвлений.