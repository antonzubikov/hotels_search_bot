# **Hotel Search Bot**

<img width="750" alt="tg_1" src="https://github.com/antonzubikov/hotels_search_bot/assets/124088976/e9fa7737-c8b8-487a-b4ee-c7f9de2ba12f">
<img width="750" alt="tg_2" src="https://github.com/antonzubikov/hotels_search_bot/assets/124088976/73d9d848-f196-4898-affe-9987ab5e5757">
<img width="750" alt="tg_3" src="https://github.com/antonzubikov/hotels_search_bot/assets/124088976/2c4f76dc-d3b5-41e0-b7df-c1096e803069">


## Project description:
Это телеграм бот, с помощью которого можно получать информацию об отелях, расположенных по всему миру по разным критериям. В работе используется Rapid API.

## Used technologies:

* Python (3.10);
* PyTelegramBotAPI (Telegram Bot framework; 4.7.0);
* SQLite3 (relational database; 3.39.5);
* requests (2.28.1);
* telebot–calendar (Telegram calendar display tool; 1.2)


## Installation:

1. Необходимо скопировать всё содержимое репозитория в отдельный каталог;
2. Установить все библиотеки из файла 'requirements.txt';
3. Файл '.env.template' переименовать в '.env'. Откройте его и заполните необходимыми данными. Для этого вам надо:
    * Создать своего бота с помощью @BotFather, запросить токен;
    * Зарегистрироваться на сайте [rapidapi.com/apidojo/api/hotels4/](), скопировать API ключ (вкладка My Apps —> Ваш API ключ —> Security)
4. Запустить файл **main**.py


## Bot commands:

* /start — запуск бота;
* /help — помощь по командам бота;
* /lowprice — вывод самых дешёвых отелей в городе;
* /highprice — вывод самых дорогих отелей в городе;
* /bestdeal — вывод отелей, наиболее подходящих по цене и расположению от центра;
* /history — вывод истории поиска отелей
