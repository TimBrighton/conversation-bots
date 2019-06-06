# Разговорные чат-боты для общения в Telegram и Вконтакте с использованием DialogFlow
### Автор проекта: Алексей Свирин, телеграм — [@svirin](https://telegram.me/svirin)
### Цель проекта: создание автономных чат-ботов для мессенджера Телеграм и социальной сети ВКонтакте

Боты отвечают пользователю на сообщения, боты работают на одной бозе фраз, которая загружена в DialogFlow. Ботов можно быстро обучить благодаря дополнительно реализованным функциям.

Боты, с которыми можно поговорить:
1) Телеграм. Для старта необходимо ввести команду /start
2) ВКонтакте. Бот отвечает на личные сообщения данной группы

![](working_bot.gif)

# Как установить
### Этап 1. Для запуска бота необходимо получить ключи от нескольких сервисов

# Требования
Все требуемые модули указаны в файле requirements.txt  
Для установки запустите команду:
```python
python3 pip install -r requirements.txt
```

# Требования к запуску на Heroku
Для запуска на Heroku необходимы файлы Procfile и Pipfile:
1) В файле Procfile прописано какой файл нужно запускать на Heroku.
2) В файлах Pipfile и reqirements.txt указаны необходимые модули для работы бота.
