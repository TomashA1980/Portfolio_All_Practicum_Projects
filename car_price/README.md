# Оценки стоимости автомобиля( рекомендательная система)

[html](https://github.com/TomashA1980/Portfolio_All_Practicum_Projects/blob/main/car_price/car_price.html)    [ipynb](https://github.com/TomashA1980/Portfolio_All_Practicum_Projects/blob/main/car_price/car_price.ipynb)

## Описание проекта

Нужно быстро узнать рыночную стоимость автомобиля. На основе исторические данные необходимо построить модель для определения стоимости автомобиля.


## Навыки и инструменты

- **python**
- **pandas**
- **numpy**
- **seaborn**
- scipy**.stats**
- sklearn: **LinearRegression, Ridge, SGDRegressor, DecisionTreeRegressor, RandomForestRegressor, DummyRegressor, Pipeline**
- **optuna** 
- **LGBRegressor**



## Вывод

Перед обученим модели мы сделали следующую работу:

- познакомились с данными
- удалили дубликаты
- выбрали только важные признаки
- убрали аномалии данных.

Задание проекта выполнено. Мы нашли модель соотвествующую критериям заказчика:

- качество предсказания было высокое: RMSE меньше 2500,
- скорость предсказания была низкой: измерение в секундах
- время обучения было низким: измерение в секундах Более того мы встроили в модель предобработку данных.

