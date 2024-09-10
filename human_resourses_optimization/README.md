# Прогноз удовлетворённости сотрудников компании и их возможности увольнения

## Описание проекта

Требуется построить модель, которая сможет предсказать уровень удовлетворённости сотрудника на основе данных заказчика.

Также требуется построить модель, которая сможет на основе данных заказчика предсказать то, что сотрудник уволится из компании.

## Навыки и инструменты

- pandas
- numpy
- matplotlib
- seaborn
- sklearn.model_selection.**GridSearchCV**
- sklearn.pipeline.**Pipeline**
- sklearn.metrics.**make_scorer**
- sklearn.metrics.**f1_score**
- sklearn.metrics.**roc_auc_score**
- sklearn.linear_model.**LinearRegression**
- sklearn.linear_model.**LogisticRegression**
- sklearn.tree.**DecisionTreeRegressor**
- sklearn.tree.**DecisionTreeClassifier**
- sklearn.svm.**SVR**
- sklearn.svm.**SVC**
- sklearn.dummy.**DummyRegressor**
- sklearn.dummy.**DummyClassifier**

## 

## Общий вывод

Была проведена предобработка, были заполнены пропуски и исправлены опечатки. При решении первой задачи, из трёх моделей была выбрана SVR, при решении второй, из трёх моделей была выбрана SVC. Был построен портрет медианного сотрудника.
