# Исследование надежности заемщиков
## Описание проекта
Заказчик — кредитный отдел банка.   
Результаты исследования будут учтены при построении модели кредитного скоринга — специальной системы, которая оценивает способность потенциального заёмщика вернуть кредит банку.

Цель исследования:

Выяснить, влияет ли семейное положение и количество детей клиента на факт погашения кредита в срок. Входные данные от банка — статистика о платёжеспособности клиентов. 

Данные:  
— количество детей в семье  
— общий трудовой стаж в днях  
— возраст клиента в годах  
— уровень образования клиента  
— идентификатор уровня образования  
— семейное положение  
— идентификатор семейного положения  
— пол клиента  
— тип занятости  
— имел ли задолженность по возврату кредитов  
— ежемесячный доход  
— цель получения кредита  

## Инструменты
`предобработка данных` `Python` `Pandas`

## Выводы

По итогам исследования мы можем предположить:
- есть зависимость между количеством детей и возвратом кредита в срок:  с увеличеснием количества детей у клиента он с большей вероятностью будет иметь задолженность по кредиту.
- есть зависимость, между семейным положением и возвратом редита в срок: вдовцы своевременнее всех платят по кредитам, в то время, как люди, никогда не состоящие в браке чаще имеют проблемы со своевременностью оплаты по кредиту.
- есть зависимость между уровнем дохода и возвратом кредита в срок: с ростом дохода количество должников растет до определенного уровня (до дохода в диапазоне 132113 - 161381), а потом начинает снижаться. Меньше всего должников с доходом от 214605.
- есть зависимость между уровнем дохода и возвратом кредита в срок: клиенты, котрые берут кредиты на операции с недвижимостью, реже всех имеют задолженности по кредиту, в то время, как люди, берущие кредит на операции с автомобилем, чаще других имеют задолженности по кредиту.

## [Cмотреть ход решения](https://github.com/laringerman/data_analyst_portfolio/blob/main/01-bank_data/1.0-lgg-borrower_analysis.ipynb)
