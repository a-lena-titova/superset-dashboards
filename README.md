# superset-dashboards
## Дэшборды в Superset, сделанные мной во время прохождения симулятора аналитика Karpov Courses

⚡ Предыстория:
Мы (аналитики) работаем в некой социальной сети, в которой есть лента новостей и мессенджер. В компании пока не выстроены аналитические процессы, и мы будем начинать с самого нуля. Первое, с чего нужно начать, — это базовые дашборды, которые покрывают собой ключевые аудиторные метрики и ключевые события нашего продукта. Сделаем так, чтобы мы могли без труда и ручных выгрузок отвечать на самые простые вопросы о нашем приложении.


### 🎓 Основной дашборд по ленте новостей за прошлое время: https://superset.lab.karpov.courses/superset/dashboard/1516/
Что смотрим на этом дэшборде: 
- Основные аудиторные показатели: DAU, WAU, MAU
- Основные события: лайки, просмотры, CTR
- Топ постов, топ юзеров
- Дополнительные аудиторные данные: Кол-во событий на пользователя, Stickness ratio (DAU / MAU), DAU в России (основной рынок), DAU по другим странам


### 🎓 Оперативный дашборд по ленте новостей с графиками за сегодняшний день: https://superset.lab.karpov.courses/superset/dashboard/1515/
Что смотрим на этом дэшборде: 
- Уникальные пользователи: сегодня, вчера, неделю назад
- Сумма событий: сегодня, вчера, неделю назад
- События на 1 уникального пользователя: сегодня, вчера, неделю назад
- Просмотры: сегодня, вчера, неделю назад
- Лайки: сегодня, вчера, неделю назад
- CTR: сегодня, вчера, неделю назад


### 🎓 Дашборд, который описывает взаимодействие двух сервисов — ленты и сообщений: http://superset.lab.karpov.courses/r/1454
Что смотрим на этом дэшборде:

Аудиторные данные ВСЕГО ПРИЛОЖЕНИЯ и ПО ПРОДУКТАМ:
- Какая у нашего приложения активная аудитория по дням, т.е. пользователи, которые пользуются и лентой новостей, и сервисом сообщений
- Какая у ленты новостей активная аудитория по дням
- Какая у мессенджера активная аудитория по дням
- Сколько событий происходит в приложении за день, какие это события

Аудиторные данные ПО ПЕРЕСЕЧЕНИЮ ПРОДУКТОВ (ленты и мессенджера)
- Сколько пользователей использует только ленту новостей и не пользуются сообщениями
- Сколько пользователей использует только мессенджер и не пользуются лентой
- Сколько пользователей использует и ленту новостей и мессенджер
