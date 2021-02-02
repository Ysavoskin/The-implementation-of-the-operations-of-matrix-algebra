# Coursework on the topic "Implementation of matrix algebra operations in modeling processes in a linear dynamical system»

Задав значения фазовых координат для векторая начального состояния X(0) динамической системы размерности Nx1, а также элементы переходной матрицы Ф размерности NxN.
Осуществление моделирования динамики процесса по формуле: X(k+1) = Ф * X(k), где k = 0, 1, 2 ... N-1, а N количество шагов по времени.

**Результат работы:**

Введите количество строк и столбцов матрицы Ф: 3

matrix[1][1] = 3

matrix[1][2] = 1

matrix[1][3] = 2

matrix[2][1] = 1

matrix[2][2] = 4

matrix[2][3] = 1

matrix[3][1] = 2

matrix[3][2] = 2

matrix[3][3] = 3

Введите элементы вектора X(0):

vector[1] = 1

vector[2] = 3

vector[3] = 2

Введите количество шагов N: 4

Введенная матрица Ф:

3   1   2

1   4   1

2   2   3



Введенный вектор X(0):

1

3

2



Результирующий вектор X(1):

10

15

14



Результирующий вектор X(2):

73

84

92


Результирующий вектор X(3):

487

501

590

runtime = 20,231000

**Визуализация результата работы:**

![screenshot of sample](https://raw.githubusercontent.com/Ysavoskin/The-implementation-of-the-operations-of-matrix-algebra/main/Visual.png)
