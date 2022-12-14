# Архитектура приложения

## Класс LinearSystem
Содержит следующие поля:\
matrix - двумерная матрица коэффициентов вещественного типа. Содержит в себе также матрицу свободных членов;\
n_rows - количество уравнений в системе;\
n_cols - количество переменых в системе (с учетом столбца свободных членов);\
answer - матрица-столбец типа Answer. Решение системы.

## Класс Answer
vector - матрица-столбец вещественного типа. Решение системы;\
size - количество переменных в решении.\

## Класс Calculator
linearSystem - линейная система уравнений; \
systemGrid - таблица для коэффициентов системы; \
constantGrid - таблица для свободных членов системы; \
answerGrid - таблица для решения системы;\
calcButton - кнопка для решениz системы;\
changeRowsButton - меню для выбора количества уравнений системы;\
changeColsButton - меню для выбора количество переменных в системе.

Изображение с архитектурой:

![UML диаграмма](https://github.com/Pivosaurus-Co/Application-for-solving-system-of-linear-equations/blob/6c4e428d9e2ac45ec762277ad8ecda76c6d6eaa3/docs/uml_diagram.png)
