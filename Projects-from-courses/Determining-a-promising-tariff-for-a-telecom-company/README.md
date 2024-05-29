# Определение перспективного тарифа для телеком-компании. Анализ тарифов мобильного оператора
### Описание проекта
Необходимо на небольшой выборке сделать предварительный анализ тарифов. Проанализировать поведение клиентов и сделать вывод - какой тариф лучше.
### Навыки и инструменты
**Теги: маркетинг, телеком**

<img src="https://img.shields.io/badge/Pandas-black?style=flat-square&logo=pandas&logoColor=orange"/><img src="https://img.shields.io/badge/MatPlotlib-black?style=flat-square"/><img src="https://img.shields.io/badge/SciPy-black?style=flat-square&logo=scipy&logoColor=orange"/>
## Сферы деятельности:
Маркетинг-аналитик, Бизнес-аналитика, Статический анализ, Data Analyst
## Основные пункты исследования:
 - Изучение данных. Просмотр общей информации
 - Предобработка (категоризация, структурирование, создание дополнительного датафрейма)
 - Анализ данных (оцнека количества минут разговора, количества сообщений, объёма интернет-трафика потребляемых пользователями)
 - Проверка гипотез (выручка разных тарифов, выручка с разных регионов)

## Выводы и результаты
Оказалось, действительно, средняя прибыль в друх тарифах отличается, более того, мы заметили, что средние израсходованные количества звонков, сообщений и объёма интернет-трафика не сильно отличаются между тарифами, 
тогда как базовая стоимость тарифов отличается почти в 4 раза. 

Прибыль от тарифа "Ультра" выше, чем прибыль от тарифа "Смарт". Однако итоговая стоимость услуг даже с переплатами остаётся меньше у тарифа "Смарт", 
что делает его более выгодным для пользователя. 

Доход из Москвы и из регионов сильно не отличается, каждая категория приносит деньги. 

Стоит подумать надо оптимизацией тарифов. Для пользователей тарифа "Смарт" не 
редкость выйти за включённый пакет услуг, тогда как у пользователей тарифа "Ультра" часто есть неизрасходованный пакет услуг (сообщений так вообще часто 80%).