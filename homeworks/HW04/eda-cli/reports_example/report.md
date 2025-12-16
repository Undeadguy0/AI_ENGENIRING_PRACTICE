# EDA-отчет

Исходный файл: `example.csv`

Строк: **36**, столбцов: **14**

## Качество данных (эвристики)

- Оценка качества: **0.74**
- Макс. доля пропусков по колонке: **5.56%**
- Слишком мало строк: **True**
- Слишком много колонок: **False**
- Слишком много пропусков: **False**

## Колонки

Колонки с количетвом нулей выше порога 38.3 %
user_id: **100.0 %** 
sessions_last_30d: **100.0 %** 
avg_session_duration_min: **94.44444444444444 %** 
pages_per_session: **100.0 %** 
purchases_last_30d: **100.0 %** 
revenue_last_30d: **100.0 %** 
churned: **100.0 %** 
signup_year: **100.0 %** 
n_support_tickets: **100.0 %** 


См. файл `summary.csv`.

Среднее по всем колонкам:
user_id: 1018.194
sessions_last_30d: 11.944
avg_session_duration_min: 7.247
pages_per_session: 4.100
purchases_last_30d: 1.139
revenue_last_30d: 1575.014
churned: 0.333
signup_year: 2020.972
n_support_tickets: 1.083


## Пропуски

См. файлы `missing.csv` и `missing_matrix.png`.

## Корреляция числовых признаков

См. `correlation.csv` и `correlation_heatmap.png`.

## Категориальные признаки

См. файлы в папке `top_categories/`.

## Гистограммы числовых колонок

См. файлы `hist_*.png`.
