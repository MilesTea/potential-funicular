#  Бот Vk Tinder
### Курсовое задание, выполнение для курса Python разработчик от  netology

Бот для поиска пары по вашим параметрам (возраст, пол, город)

Написан с использованием базы данных SQLite (Для большей гибкости)

###Для корректной работы вам потребуется
1. Установленный Python интерпретатор
2. Установленные зависимости проекта (pip install -r requirements.txt)
3. Ключ доступа вашего сообщества с включенным Long Poll Api [Получение ключа доступа](https://vk.com/dev/access_token?f=2.%20%D0%9A%D0%BB%D1%8E%D1%87%20%D0%B4%D0%BE%D1%81%D1%82%D1%83%D0%BF%D0%B0%20%D1%81%D0%BE%D0%BE%D0%B1%D1%89%D0%B5%D1%81%D1%82%D0%B2%D0%B0) | [Включение Long Poll Api](https://vk.com/dev/bots_longpoll)
4. Id вашего приложение в ВК [Ссылка для создания приложения](https://vk.com/apps?act=manage)
5. Получить ключ доступа пользователя по ссылке, заменив client_id id своего приложения (ключ доступа будет передан в браузерной строке в параметре access_token)
```
https://oauth.vk.com/authorize?client_id=(id вашего приложения)&display=page&redirect_uri=https://oauth.vk.com/blank.html&response_type=token&v=5.131
```

####После запуска, для начала работы необходимо будет написать сообщение сообществу, от лица которого вы получили ключ доступа