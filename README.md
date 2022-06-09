## Чат на Django используя channels + redis

## Установка и запуск
### 1. Установка зависимостей
`pip install -r requirements.txt`

### 2. Запуск redis в докере 
`docker run -p 6379:6379 -d redis:5`

### 3. Запустить джанго проект 
`python manage.py runserver`

### 4. Открыть чат по адресу: 
http://127.0.0.1:8000/chat/ <название_комнаты>



