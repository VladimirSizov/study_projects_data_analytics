## Анализ маркетинговых расходов интернет-магазина
https://github.com/VladimirSizov/study_projects_data_analytics/blob/main/marketing_traffic_analysis.ipynb

Отдел маркетинга обратился к аналитикам с просьбой проанализировать:
- чувствительные показатели аудитории  
- оценить качество покупателей  
- расходы отдела маркетинга  

подготовить обоснование для оптимизации работы с каналами привлечения.  
Мы работаем с приложением в котором пользователи совершают внутренние покупки.  
Имеются данные за период с 2019-01-01 по 2019-30-09   
Прежде чем совершить покупки пользователи знакомятся с товарами.  

Задачи посчитать и проанализировать:

Аудитория:  
- размер аудитории, MAU, WAU, DAU  
- качество взаимодействия, количество сессий, просмотров на сессию, фактор залипания  
- RR показатель удержания пользователей  

Продажи:  
- GM валовая прибыль  
- количество покупателей, количество покупок, покупок на пользователя  
- средний чек  
- CR1 конверсия в покупку, время первой покупки после установки  
- ARPPU средний доход на покупателя  

Источники трафика и маркетинг:  
- расходы на рекламу всего и по источникам  
- стоимость привлечения покупателя по источникам  
- LTV прибыль которую приносит клиент  
- ROMI коэффициент возврата маркетинговых инвестиций  

<hr>

## Влияние погодных условий на прогнозирование количества аренд велосипедов в Лондоне
https://github.com/VladimirSizov/study_projects_data_analytics/blob/main/time_series_with_prediction.ipynb  

В этом блокноте представлен анализ количества аренды велосипедов в Лондоне c 2015-01-04 по 2017-01-03.

Мы будем исследовать:
- какие факторы погодных условий и на сколько влияют на изменения количества аренды велосипедистов.
- как сезонность, праздничные дни и погодные условия (влажность, температура, скорость ветра) влияют на точность предсказаний количества аренд велосипедов.

Мы используем метод линейной регрессии для определения размера влияния, а также библиотеку fbprophet для предсказания количества аренды велосипедов. Fbprophet реализует обобщенную аддитивную модель и моделирует временной ряд как сумму различных компонентов (нелинейный тренд, периодические компоненты и праздники или особые события) и позволяет включать регрессоры.

<hr>

## Определение отношения между значениями индексов миролюбия и уровня образования в разных странах мира
https://github.com/VladimirSizov/study_projects_data_analytics/blob/main/determination_relationship_between_peacefulness_and_education.ipynb

Кажется интуитивно очевидным предположение что в странах с более высоким уровнем образования общество более осознанно, более внимательно к окружающим и поэтому менее агрессивно по сравнению с странами обладающими низким уровнем образования. Проверим так ли это на самом деле.

Глобальный индекс миролюбия (Global Peace Index) — это комплексный показатель, который характеризует миролюбие стран мира, измеряя уровень насилия внутри государства и уровень агрессивности его внешней политики. 
Индекс уровня образования в странах мира (Education Index) — комбинированный показатель Программы развития Организации Объединённых Наций (ПРООН), который измеряет достижения страны с точки зрения достигнутого уровня образования её населения. источник данных

В этом ноутбуке с помощью метода линейной регрессии мы определим зависимость этих двух величин, посмотрим насколько хорошо модель описывает эти данные

<hr>

##Как я учил английский


В какой-то момент я осознал что мне необходимо расширить свой лексикон английских слов.
Самая большая сложность как выяснилось в процессе - это овладеть первыми 300-500 словами.

В этом ноутбуке я разобрал результаты того как проходила часть моего обучения до тысячи слов.
Мне было интересно написать самому тест с помощью которого я смог бы расширить свой лексикон.
http://ayumu.ru/ здесь каждый желающий может проделать тот же путь что и я.

<hr>

## Кластеризация K-средних
https://github.com/VladimirSizov/study_projects_data_analytics/blob/main/kmeans_clusterization.ipynb

Кластеризация K-средних, распространённый алгоритм неконтролируемого машинного обучения.

Определение кластеров осуществляется на схожести данных у экземпляров.

Мы подробно рассмотрим метод подбора координат центройдов, разделения данных на кластеры, а также нарисуем результат на графике.
