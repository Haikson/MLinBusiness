### Итоговый проект курса "Машинное обучение в бизнесе"

Стек:
1. ML: sklearn, pandas, numpy
2. API: flask

Данные: с kaggle - https://www.kaggle.com/danofer/sarcasm

Задача: предсказать по комментарию и ответу, также теме беседы, является ответ сарказмом или нет (поле label). Бинарная классификация

Используемые признаки:
1. comment (text)
2. parent_comment (text)
3. subreddit (text)

Преобразования: tfidf

Модель: logreg
