# Телеком
## Задача
Оператор связи хочет научиться прогнозировать отток клиентов. Если выяснится, что пользователь планирует уйти, ему будут предложены промокоды и специальные условия. Команда оператора собрала персональные данные о некоторых клиентах, информацию об их тарифах и договорах.

## Описание полей данных:
- BeginDate – дата начала пользования услугами,
- EndDate – дата окончания пользования услугами,
- Type – тип оплаты: ежемесячный, годовой и тд,
- PaperlessBilling – безналичный расчет,
- PaymentMethod – способ оплаты,
- MonthlyCharges – ежемесячные траты на услуги,
- TotalCharges – всего потрачено денег на услуги
- Dependents – наличие иждивенцев
- Senior Citizen – наличие пенсионного статуса по возрасту
- Partner – наличие супруга(и)
- MultipleLines – наличие возможности ведения параллельных линий во время звонка


## Основные выводы
На исходных данных были обучены и сравнены модели машинного обучения - "Случайный лес", "Логистическая регрессия" и "Градиентный бустинг". Было установлено, что лучше всего предсказывает отток клиентов модель "Градиентный бустинг" с параметрами learning_rate=0.03, max_depth=25, n_estimators=1000. Итоговое качество: ROC-AUC 0,9259.

## Статус проекта
Проект закончен.

## Используемые библиотеки
- pandas
- seaborn
- matplotlib
- numpy
- sklearn
- lightgbm
- statsmodels
- scipy
- warnings

