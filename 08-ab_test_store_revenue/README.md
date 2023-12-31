# A/B тест в интегрнет магазине
## Описание проекта

Совместно с отделом маркетинга был подготовлен список гипотез для увеличения выручи.

Цель исследования:

- приоритизация гипотез, 
- запуск A/B-теста,  
- анализ результатов A/B-теста.

Данные:  
- краткое описание гипотезы;
- охват пользователей по 10-балльной шкале;
- влияние на пользователей по 10-балльной шкале;
- уверенность в гипотезе по 10-балльной шкале;
- затраты ресурсов на проверку гипотезы по 10-балльной шкале. Чем больше значение Efforts, тем дороже проверка гипотезы;
- 
- идентификатор заказа;
- идентификатор пользователя, совершившего заказ;
- дата, когда был совершён заказ;
- выручка заказа;
- группа A/B-теста, в которую попал заказ;
- 
- дата;
- группа A/B-теста;
- количество пользователей в указанную дату в указанной группе A/B-теста.


## Инструменты

`Python` `Pandas` `Matplotlib` `SciPy` `A/B-тестирование` `проверка статистических гипотез`

## Выводы

Провели приоритезацию гипотез.  

По методу ICE лучше отдать приоритет гипотезам 9, 1, 8.
По методу RICE (т.е. с учетом охвата пользователей) лучше отдать приоритет гипотезам 8 (с большим отрывом), 3, 1.  

Изучили результаты A/B теста.  

Результаты по “сырым” данным:  

- В среднем количестве заказов на пользователя между группами есть статистически значимые различия. Относительный прирост среднего группы B к конверсии группы A равен 13.8%.
- Статистически значимых различий в среднем чеке заказа между группами нет. Средний чек группы B больше среднего чека группы А на 26%.

Результаты по отфильтрованным данным:  

- В среднем количестве заказов на пользователя между группами есть статистически значимые различия. Относительный прирост среднего группы B к конверсии группы A равен 14.8%.
- Статистически значимых различий в среднем чеке заказа между группами нет. Средний чек группы B меньше среднего чека группы А на 2%.
  
  
**Рекомендации**  
Остановить A/B-тест. Мы увидели рост конверсии у группы B, что практически не повлияло на средний чек.  
проверить деление трафика на группы, т.к. есть 58 пользователей (их id в датафрейме intersecting_id_list), которые попали в обе группы тестирования, возможно это шибка деления, и, может быть, это id сотрудников компании, которые проводили тестирование.

## [Cмотреть ход решения](https://github.com/laringerman/data_analyst_portfolio/blob/main/08-ab_test_store_revenue/1.0-lgg-a_b_test.ipynb)
