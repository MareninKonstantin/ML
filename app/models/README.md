python-flask-docker

Итоговый проект курса "Машинное обучение в бизнесе"

Стек:

ML: sklearn, pandas, numpy API: flask Данные: с kaggle - https://www.kaggle.com/competitions/titanic

Задача: предсказать по описанию пассажира, выжил он или нет (поле Survived). Бинарная классификация

Используемые признаки:

Pclass (int)
Sex (text)
Age (float)
SibSp (int)
Parch (int)                                            
Fare (float)
Cabin (text)
Embarked (text)

Преобразования признаков: OHE

Модель: logreg
