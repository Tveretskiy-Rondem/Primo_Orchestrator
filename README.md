# Dashboard для мониторинга событий оркестратора.
Для функционирования борды необходимо подключение БД оркестратора ltools и ltoolslogs в качестве одноименных datasource.
Версия Grafana 9.4.7 или выше.

# ВАЖНО!
Счетчики Logs и OrchEvents создают высокую нагрузку на БД. Если нет крайней необходимости в постоянной визуализации количества записей в таблицах Logs и OrchEvents, рекомендуется их не использовать.
