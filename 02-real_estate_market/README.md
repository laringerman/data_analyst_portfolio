# Исследование объявлений о продаже квартир
## Описание проекта
В нашем распоряжении данные сервиса Яндекс.Недвижимость — архив объявлений о продаже квартир в Санкт-Петербурге и соседних населённых пунктов за несколько лет. По каждой квартире на продажу доступны два вида данных. Первые вписаны пользователем, вторые — получены автоматически на основе картографических данных.
  
Цель исследования:  
  
Провести исследовательский анализ данных, который поможет установить параметры, влияющие на цену объектов.   
  
Данные:  
— расстояние до ближайшего аэропорта в метрах (м)  
— число балконов  
— высота потолков (м)  
— расстояние до центра города (м)  
— сколько дней было размещено объявление (от публикации до снятия)  
— дата публикации  
— этаж  
— всего этажей в доме  
— апартаменты (булев тип)  
— площадь кухни в квадратных метрах (м²)  
— цена на момент снятия с публикации  
— жилая площадь в квадратных метрах (м²)  
— название населённого пункта  
— свободная планировка (булев тип)  
— число парков в радиусе 3 км  
— расстояние до ближайшего парка (м)  
— число водоёмов в радиусе 3 км  
— расстояние до ближайшего водоёма (м)  
— число комнат  
— квартира-студия (булев тип)  
— общая площадь квартиры в квадратных метрах (м²)  
— число фотографий квартиры в объявлении  

## Инструменты
`Python` `Pandas` `Matplotlib` `предобработка данных` `исследовательский анализ данных` `визуализация данных`

## Выводы

- Между площадью объекта и его ценой есть положительная корреляция.
- Между количеством комнат объекта и его ценой также есть положительная корреляция.
- Объекты находящиеся между первым и последним этажом в среднем дорожи, объекты на первом этаже - с самой низкой в среднем ценой.
- У объявлений, выложенных во вторник, среду и четверг средняя цена выше, чем у объявлений, выложенных в понедельник, пятницу, субботу и восресенье.
- В март и июль в среднем самые низние цены, а в сентябре - самые высокие.
- С 2014 года по 2018 год был спад средней цены объекта, и к 2019 году только начался подъем.
- Больше всего объявлений в Санкт-Петербурге, Мурино, Кудрово, поселке Шушары, Всеволожске, Колпино, поселке Парголово, Пушкине, Гатчине и Выборге (в порядке убывания количества объявлений).
- Населенные пункты с самой высокой ценой за квадратный метр: Санкт-Петербург, Пушкин, Кудряво (в порядке убывания цены).
- Населенные пункты с самой низкой ценой за квадратный метр: Выборг, Гатчина, Всеволожск (в порядке возрастания цены).
- С удалением от центра, цена квадратного метра объекта в седнем уменьшается.


## [Cмотреть ход решения](https://github.com/laringerman/data_analyst_portfolio/blob/main/02-real_estate_market/1.0-lgg-real_estate.ipynb)
