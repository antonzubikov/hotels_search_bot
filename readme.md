# **Hotel Search Bot**


## Project description:
Это телеграм бот, с помощью которого можно получать информацию об отелях, расположенных по всему миру по разным критериям. В работе используется Rapid API.

## Used technologies:

* Python (3.10);
* PyTelegramBotAPI (Telegram Bot framework; 4.7.0);
* SQLite3 (relational database; 3.39.5);
* requests (2.28.1);
* telebot–calendar (Telegram calendar display tool; 1.2)


## Installation:

1. Необходимо скопировать все содержимое репозитория в отдельный каталог;
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
