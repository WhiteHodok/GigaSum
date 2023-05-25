![image](https://github.com/WhiteHodok/GigaSum/assets/39564937/39bd4836-a18d-4878-b933-5a212b770492)

src for bot from : https://github.com/tpai

# SGPT


- RUS Bot: https://t.me/SGPTRUS_bot


# Если ты камушек и только начинаешь изучать змею:
- Открой файл bot.py и найди там 11 строчку
- Поменяй значения этих строчек на свои (в Usage всё расписано, это ниже)
- Запусти файл start_bot.bat


## Features

- Поддержка текста
- Поддержка URL`s
- Поддержка PDF
- Поддержка ютуб-видео (не ШОРТСЫ!)

## Usage

| Переменная           | Описание |
|----------------------|-------------|
| telegram_token       | Ваш токен с OpenAI (https://platform.openai.com/account/api-keys) (required) |
| apikey               |  Ваш токен с OpenAI (https://platform.openai.com/account/api-keys) (default: gpt-3.5-turbo) |
| model                | Модель (выбирайте между 3.5 турбо и давинчи 003, всё остальное не корректно робит) (required) |
| lang              | Язык текста для анализа (default: Russian) |


```sh
# Установка библиотек
pip install -r requirements.txt

py bot.py



