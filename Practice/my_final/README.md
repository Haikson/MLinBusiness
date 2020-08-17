### Итоговый проект курса "Машинное обучение в бизнесе"

Стек:
1. ML: sklearn, pandas, numpy
2. API: flask

Данные: с kaggle - https://www.kaggle.com/shivamb/real-or-fake-fake-jobposting-prediction

Задача: предсказать по описанию вакансии является ли она фейком или нет (поле fraudulent). Бинарная классификация

Используемые признаки:
1. description (text)
2. company_profile (text)
3. benefits (text)

Преобразования: tfidf

Модель: logreg
