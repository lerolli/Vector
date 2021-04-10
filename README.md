# Задача №1 - практика по ООП осень 2020

Требуется реализовать несколько классов для проведения математических операций над векторами. 

**Необходимые классы:**
- Vector3d - трехмерный
- Vector5d - пятимерный
- Vector7d - семимерный
- VectorNd - произвольной размерности.

В каждом классе должны быть реализованы следующие операции:
1. Сложение
2. Вычитание
3. Скалярное произведение
4. Векторное произведение - для Vector3d
5. Сравнение по координатам
6 Строковое представление
7. Метод hashCode()

Классы векторов должны быть неизменяемыми. Применение операции между двумя векторами приводит к появлению нового объекта вектора - результата

Сигнатуры методов должны быть ограничены тем классом, в котором используются. Это означает, что если вызывается метод add у Vector3d, то и аргументом он ожидает Vector3d.
И результатом выполенния тоже является Vector3d - то есть сложение трехмерных векторов дает трехмерный вектор, сложение пятимерных - пятимерный. И т.д.

Общая логика операций должна быть вынесена, чьи методы должны быть описаны в интерфейсе. Необходимо рукводствоваться принципом разумности, т.е. использвоать тольком минимально необходимый набор логических единиц.

Дополнительная задача: Необходимо все методы покрыть тестами для проверки работоспособности библиотеки.