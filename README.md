# Yatube API
### Описание
API для социальной сети блогеров.
### Технологии
Python, Django, DRF
### Запуск проекта в dev-режиме
- Установите и активируйте виртуальное окружение
- Установите зависимости из файла requirements.txt
```
python3 -m pip install --upgrade pip pip install -r requirements.txt
``` 
- В папке с файлом manage.py выполните миграции:
```
python3 manage.py migrate
```
- Запустить проект:
```
python3 manage.py runserver
```
После запуска проекта документацию к API читай в [Redoc](http://127.0.0.1:8000/redoc/)

### Автор
Евгений Голодных
