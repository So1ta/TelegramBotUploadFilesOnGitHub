# Телеграмм бот для загрузки файлов в ваш репозиторий GitHub.

Бот принимает любые файлы, фото, видео, текст. Однако множество файлов он принимать не может.

![Image alt](https://So1ta.github.io/imagetg.png)

Язык бота - Python 3.12

В файле bot.py вы должны вписать ваш GITHUB_TOKEN, GITHUB_USERNAME, GITHUB_REPOSITORY, YOUR_BOT_TOKEN(токен бота телеграмм) в следующих строчках:
```
# Ваши данные для GitHub
GITHUB_TOKEN = "GITHUB_TOKEN"
GITHUB_USERNAME = "GITHUB_USERNAME"
GITHUB_REPOSITORY = "GITHUB_REPOSITORY"
 
# Замените 'YOUR_BOT_TOKEN' на токен вашего бота
BOT_TOKEN = 'YOUR_BOT_TOKEN'
```
После чего запустите бота (не забудьте установить пакеты для его работы).
Пакеты:
* python-telegram-bot 21.4
* PyGithub 2.3.0
```
pip install python-telegram-bot
pip install PyGithub
```

В телеграмм боте BotReader(исходное название) существуют 2 кнопки:
* Отправить сообщение на GitHub
* Очистить репозиторий GitHub
По кнопке **Отправить сообщение на GitHub** вы можете отправить любой файл сообщением, в том числе обычный текст.

По кнопке **Очистить репозиторий GitHub** вы можете полностью очистить репозиторий.

> [!IMPORTANT]
> Важно включить разрешения в репозитории на сайте GitHub для того, чтобы файлы загружались!!!
