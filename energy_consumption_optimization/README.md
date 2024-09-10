# Прогноз конечной температуры сплава

## Описание проекта

Требуется спрогнозировать количество заказов такси на следующий час, чтобы привлекать больше водителей в период пиковой нагрузки.

## Навыки и инструменты

- pandas
- numpy
- matplotlib
- seaborn
- sklearn.model_selection.**GridSearchCV**
- sklearn.model_selection.**TimeSeriesSplit**
- statsmodels.tsa.seasonal.**seasonal_decompose**
- sklearn.model_selection.**TimeSeriesSplit**
- sklearn.model_selection.**GridSearchCV**
- sklearn.metrics.**mean_absolute_error**
- sklearn.linear_model.**LinearRegression**
- sklearn.tree.**DecisionTreeRegressor**
- catboost.**CatBoostRegressor**
- lightgbm.**LGBMRegressor**
- sklearn.dummy.**DummyRegressor**

## 

## Общий вывод

Для анализа данных, был исследован процесс обработки стали, после чего была выполнена предобработка, во время которой были удалены нереалистичные данные и утечка данных. Проведено исследование четырёх типов моделей, выбрана линейная регрессия.
