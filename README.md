# Тестовое задание на вакансию “Специалист по тестированию ПО"
## Задание 1. Написание тестовой документации для страницы "Новостройки" сайта "Этажи".

* [Чек-лист](https://docs.google.com/spreadsheets/d/10DvnD6iSPtSV7iIVjwpmkCho4qLL027bXgLtzkJH8m8/edit?usp=sharing)
* [Тест-кейс](https://docs.google.com/spreadsheets/d/1TfdovmzgSWxyBB0xU9lrFNa1czYzyxNqkvr_MyjcFSM/edit?usp=sharing)
* [Список дефектов](https://docs.google.com/spreadsheets/d/1y8qqg8TVGWHEGH3u5ZKhcK7l1tizfpE9phAQunUvBIs/edit?usp=sharing)
* [Баг-репорт](https://github.com/TatyanaKonysheva/EtagiTest/issues/1)
  
## Задание 2. Написание SQL запросов для таблицы customers.

  1. Запрос на вывод города и номера телефона клиентов с фамилией "Попов":

    SELECT city, phone
    FROM customers
    WHERE fio LIKE '%Попов%';
  
  1. Запрос на подсчет количества клиентов из Тюмени:
     
    SELECT COUNT(*)
    FROM customers
    WHERE city = 'Тюмень';
