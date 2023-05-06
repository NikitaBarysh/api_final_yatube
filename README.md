# Yatube API
### Описание
API для социальной сети блогеров.
### Технологии
Python, Django, DRF
### Как запустить проект:

Клонировать репозиторий и перейти в него в командной строке:

Cоздать и активировать виртуальное окружение:

```
python3 -m venv venv
```

```
source venv/bin/activate
```

```
python3 -m pip install --upgrade pip
```

Установить зависимости из файла requirements.txt:

```
pip install -r requirements.txt
```

Выполнить миграции:

```
python3 manage.py migrate
```

Запустить проект:

```
python3 manage.py runserver
```