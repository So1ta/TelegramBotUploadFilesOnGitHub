# TelegramBotUploadFilesOnGitHub
Телеграмм бот для загрузки файлов в ваш репозиторий GitHub.

> Язык бота - Python 3.12
>
> В файле bot.py вы должны вписать ваш GITHUB_TOKEN, GITHUB_USERNAME, GITHUB_REPOSITORY, YOUR_BOT_TOKEN(токен бота телеграмм) в следующих строчках:
> ```
> # Ваши данные для GitHub
> GITHUB_TOKEN = "GITHUB_TOKEN"
> GITHUB_USERNAME = "GITHUB_USERNAME"
> GITHUB_REPOSITORY = "GITHUB_REPOSITORY"
> 
> # Замените 'YOUR_BOT_TOKEN' на токен вашего бота
> BOT_TOKEN = 'YOUR_BOT_TOKEN'
> ```
> После чего запустите бота (не забудьте установить пакеты для его работы).
> Пакеты:
> * python-telegram-bot 21.4
> * PyGithub 2.3.0
> ```
> pip install python-telegram-bot
> pip install PyGithub
> ```
