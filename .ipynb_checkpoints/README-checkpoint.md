# Mobile_game_project

## Проект: 
1.	В первую очередь, интересует показатель retention. Напишите функцию для его подсчета.
2.	Проведено A/B тестирование наборов акционных предложений. На основе имеющихся данных определите, какой набор можно считать лучшим и на основе каких метрик стоит принять правильное решение.
3.	Предложите метрики для оценки результатов последнего прошедшего тематического события в игре.
 
### Задание 1
Retention – один из самых важных показателей в компании. Ваша задача – написать функцию, которая будет считать retention игроков (по дням от даты регистрации игрока). Данные имеют следующую структуру:
**problem1-reg_data.csv** – данные о времени регистрации
|reg_ts  |uid|
|-------  |---|
|906166566| 2 |
|906344325| 2 |
|906686169| 2 |
|906893386| 2 |
|906980227|2 |

**problem1-auth_data.csv** – данные о времени захода пользователей в игру
|auth_ts  |uid|
|-------  |---|
|906166566| 2 |
|924422172| 3 |
|937374732| 4 |
|947425117| 5 |
|955630339| 6 |

 
### Задание 2
Имеются результаты A/B теста, в котором двум группам пользователей предлагались различные наборы акционных предложений. Известно, что ARPU в тестовой группе выше на 5%, чем в контрольной. При этом в контрольной группе 1928 игроков из 202103 оказались платящими, а в тестовой – 1805 из 202667.
Какой набор предложений можно считать лучшим? Какие метрики стоит проанализировать для принятия правильного решения и как?
Формат данных:
|user_id|revenue|testgroup|
|-------|-------|---------|
|    1	|   0	|    b    |
|    2	|   0	|    a    |
|    3	|   0	|    b    |
|    4	|   0	|    b    |
|    5	|   0	|    b    |

 
Задание 3
В игре Plants & Gardens каждый месяц проводятся тематические события, ограниченные по времени. В них игроки могут получить уникальные предметы для сада и персонажей, дополнительные монеты или бонусы. Для получения награды требуется пройти ряд уровней за определенное время. С помощью каких метрик можно оценить результаты последнего прошедшего события?
Предположим, в другом событии мы усложнили механику событий так, что при каждой неудачной попытке выполнения уровня игрок будет откатываться на несколько уровней назад. Изменится ли набор метрик оценки результата? Если да, то как?

