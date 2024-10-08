# Прогноз количества заказов для сервиса такси

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
- sklearn.metrics.**mean_squared_error**
- sklearn.metrics.**make_scorer**
- sklearn.linear_model.**LinearRegression**
- sklearn.tree.**DecisionTreeRegressor**
- catboost.**CatBoostRegressor**
- lightgbm.**LGBMRegressor**
- sklearn.dummy.**DummyRegressor**

## 

## Общий вывод

Проведено исследование временного ряда на предмет трендовых и сезонных закономерностей, случайной составляющей. Проведено исследование четырёх типов моделей, выбрана линейная регрессия.
