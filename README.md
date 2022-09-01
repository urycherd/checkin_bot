# checkin_bot
Хакатон от Школа21 Сбера. Задача: "Разработать Telegram-бота для чекина на школьных мероприятиях."
## Оглавление

1. [Описание задачи](#описание-задачи)
2. [Архитектура проекта](#архитектура-проекта)
3. [Результаты](#результаты)
____

## Описание задачи
Полное описание задачи вы можете посмотреть [здесь.](https://github.com/hardworkerM/Checkin_Bot/blob/main/Checkin_bot_task.pdf) 

**Команда:**
[urycherd](https://github.com/urycherd) [hardworkerM](https://github.com/hardworkerM) [antr19](https://github.com/antr19) [mikabuto](https://github.com/mikabuto)

[Оглавление](#оглавление)
____
## Архитектура проекта
- /data - хранение генерируемых файлов отчётности и qr-кодов
- [/database](https://github.com/hardworkerM/Checkin_Bot/tree/main/database) - подключение базы данных и функции sql запросов
- [/deeplink](https://github.com/hardworkerM/Checkin_Bot/tree/main/deeplink) - Генерация qr-кода мероприятия
- [/handlers](https://github.com/hardworkerM/Checkin_Bot/tree/main/handlers) - хендлеры для взаимодействия бота с пользователем
- [/keyboards](https://github.com/hardworkerM/Checkin_Bot/tree/main/keyboards) - функции создания Inline и Reply клавиатур
- [/state](https://github.com/hardworkerM/Checkin_Bot/tree/main/state) - класс состояний
- [/utils](https://github.com/hardworkerM/Checkin_Bot/tree/main/utils) - вспомогательные, форматирующие функции
- app.py и create_bot.py - подключение и активизация бота.

[Оглавление](#оглавление)
____
## Результаты
![img1](https://user-images.githubusercontent.com/89844627/187899552-350bb603-bb41-40cc-9b43
![img2](https://user-images.githubusercontent.com/89844627/187899611-a37718b5-fb9a-482a-a81d-611d0c7cd8d7.jpeg)
-4ae3eea46fe6.jpeg)
![img3](https://user-images.githubusercontent.com/89844627/187899678-dcb2784d-17ef-4ac8-b538-58d1e3372ff6.jpeg)
Функционал бота [ютуб](https://youtu.be/U5yTr65kLro)<\br>

[Оглавление](#оглавление)
____
