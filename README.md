# Эксплоративный анализ и предобработка данных
## 1. Визуализация данных
Построить 5 графиков по выбранным данным.
Графики должны быть различных видов и использовать хотя бы 3 из рассмотренных на занятии библиотек.
Для каждого описать, какого типа переменные участвуют в визуализации, какова её цель (например, посмотреть на корреляцию двух величин или на распределение значений) и почему выбрали именно такой тип графика.

## 2. Проблемы качества и очистка данных
Rosbank ML Competition - Ссылка на соревнование: https://boosters.pro/champ_15

## 4. Feature Selection
Задания:
Провести анализ данных. Много хороших примеров анализа можно посмотреть здесь https://www.kaggle.com/c/kobe-bryant-shot-selection/kernels
Подготовить фичи для обучения модели - нагенерить признаков, обработать пропущенные значения, проверить на возможные выбросы, обработать категориальные признаки и др.
Обучить линейную модель, Lasso, Ridge на тех же признаках - построить сравнительную таблицу коэффициентов, сделать заключения о том, как меняется величина коэффициентов, какие зануляются. Посчитать RSS

Дополнительно:
Сравнить результаты на тестовом наборе данных - сделать train_test_split в самом начале, подготовить переменные, сравнить результаты работы классификаторов (те же 3), метрика ROC AUC
Построить PCA на подготовленных признаках, посмотреть, какие компоненты составляют наибольшую часть дисперсии целевой переменной

## 5. Работа с размерностью
Файл с заданием HW_ntv_vs_rain находится в папке с материалами занятия.
Необходимо сравнить интересы аудитории телеканалов НТВ и Дождь с помощью тематического моделирования LDA.