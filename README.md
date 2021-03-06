### A/B test analysis

### Описание и цель проекта
- Оценить корректность проведения теста
- Проанализировать результаты теста

Чтобы оценить корректность проведения теста, нужно проверить:

- пересечение тестовой аудитории с конкурирующим тестом,
- совпадение теста и маркетинговых событий, другие проблемы временных границ теста.

### Описание данных

`ab_project_marketing_events` — календарь маркетинговых событий на 2020 год.

Структура файла:

- название маркетингового события;
- регионы, в которых будет проводиться рекламная кампания;
- дата начала кампании;
- дата завершения кампании.

`final_ab_new_user` — пользователи, зарегистрировавшиеся с 7 по 21 декабря 2020 года.

Структура файла:

- идентификатор пользователя;
- дата регистрации;
- регион пользователя;
- устройство, с которого происходила регистрация.

`final_ab_events` — действия новых пользователей в период с 7 декабря 2020 по 4 января 2021 года.

Структура файла:

- `user_id` — идентификатор пользователя;
- `event_dt` — дата и время покупки;
- `event_name` — тип события;
- `details` — дополнительные данные о событии. Например, для покупок, `purchase,` в этом поле хранится стоимость покупки в долларах.

`final_ab_participants` — таблица участников тестов.

Структура файла:

- идентификатор пользователя;
- название теста;
- группа пользователя
