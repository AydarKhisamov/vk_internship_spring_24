У тебя есть датасет для ранжирования intern_task.csv.

В нём есть query_id - айдишник поисковой сессии, фичи релевантности документа запросу, rank - оценка релевантности.

Твоя задача:
- подготовить и проверить датасет;
- натренировать на любом удобном фреймворке модель, которая будет ранжировать документы по их фичам внутри одной сессии (query_id) (по вектору фичей
предсказывать ранк документа);
- посчитать метрики ранжирования для своей модели (NDCG@5 как минимум);
- оформить решение и выложить на github, gitlab.