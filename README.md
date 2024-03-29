# Проект Keylogger с Сервером

## Обзор
Этот проект представляет собой реализацию keylogger'а с серверной частью на Python. Keylogger - это программа, которая записывает нажатия клавиш на клавиатуре и может использоваться для мониторинга активности на компьютере. **Важно**: использование keylogger'а без согласия владельца компьютера является незаконным. Проект предназначен только для образовательных и исследовательских целей, а также для использования с согласия владельца компьютера.

## Состав проекта
Проект состоит из двух основных компонентов:
1. `main.cpp`: Клиентская часть keylogger'а, записывающая нажатия клавиш и отправляющая их на сервер.
2. `main.py`: Серверная часть проекта, принимающая данные от клиентов и сохраняющая их в отдельных файлах.

## Зависимости
- **Сервер**: Python и библиотека socket.
- **Клиент**: C++ с заголовочными файлами и библиотеками winsock2.

## Использование
### Запуск сервера
1. Выполните файл `main.py`.
2. Сервер будет слушать входящие подключения на заданном IP-адресе (`your_ip`) и порту (`your_port`).
3. Когда клиенты подключаются к серверу, сервер создает файлы для записи данных (`client_IP_ADDRESS_DATE_TIME.txt`).

### Запуск клиента (Keylogger)
1. Запустите файл `main.cpp`.
2. Клиентская часть начнет мониторинг клавиш и отправку данных на сервер.

**Примечание**: Убедитесь в соблюдении всех законов и норм перед использованием этой программы.

## Важно
Этот проект предоставлен исключительно для информационных и исследовательских целей. Авторы не несут ответственности за незаконное использование этой программы или нарушение чьих-либо прав. Используйте этот проект с осторожностью и с уважением к законам и приватности других пользователей.
