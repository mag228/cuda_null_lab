# cuda_null_lab
Нулевая лабораторная на перемножение матриц

Работа была написана с помощью google colab на Python 3. 
Реализован алгоритм перемножения матриц на CPU и на GPU с применением CUDA (векторное и поэлементное умножение). 
На вход подаются две квадратные матрицы размерностями от 100 до 2048. 
Осуществляется проверка корректности перемножения. 
Вычисляется время работы и ускорение. 
Вывод осуществляется в виде таблицы и графика

По результатам видим, что лучшее ускорение получается при размерностях матрицы кратных количеству нитей в блоке
Также, чем больше размерность, тем значительнее получаемое ускорение
Данные выводы актуальны и для векторного и для поэлементного умножения
