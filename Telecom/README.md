# Прогнозирование оттока клиентов телеком компании
[ipynb](https://github.com/naumovakotya/Portfolio/blob/main/Telecom/Forecasting%20the%20outflow%20of%20customers%20in%20a%20telecom%20company.ipynb)

## Описание проекта
Оператор связи «Ниединогоразрыва.ком» хочет научиться прогнозировать отток клиентов. Если выяснится, что пользователь планирует уйти, ему будут предложены промокоды и специальные условия. Команда оператора собрала персональные данные о некоторых клиентах, информацию об их тарифах и договорах.

## Навыки и инструменты
* **python**
* **pandas**
* **numpy**
* **seaborn**
* **phik**
* sklearn.dummy.**DummyClassifier**
* sklearn.metrics.**roc_auc_score**
* sklearn.metrics.**accuracy_score**
* sklearn.model_selection.**GridSearchCV**
* sklearn.model_selection.**cross_val_score**
* ssklearn.preprocessing.**OneHotEncoder**
* sklearn.pipeline.**make_pipeline**
* **RidgeClassifier**
* **RandomForestClassifier**
* **LogisticRegression**
* **CatBoostClassifier**

## Общий вывод
Было проведённо обучение данных моделей для предсказания ухода клиентов. Показатели лучшей модели `CatBoostClassifier`: 
* `AUC-ROC` = **0.911**
* `Точность` = **0.865**.
  
Самым важным признаком для модели оказалось количество дней, проведённых клиентом в компании, далее количество потраченных средств за месяц и после общее количество трат. 
