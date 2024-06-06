API проекта "Yatube"

Описание проекта

В проекте реализован интерфейс API, благодаря которому социальная сеть "Yatube"
сможет взаимодействовать с другой программой.

Использованные технологии

asgiref==3.5.2
attrs==22.1.0
Django==3.2
djangorestframework==3.12.4
iniconfig==1.1.1
packaging==21.3
Pillow==9.3.0
pluggy==0.13.1
py==1.11.0
pyparsing==3.0.9
pytest==6.2.4
pytest-django==4.4.0
pytest-pythonpath==0.7.3
pytz==2022.6
sqlparse==0.4.3
toml==0.10.2

Запуск:

Клонировать репозиторий с GitHub
```
git clone 
```

Установить виртуальное окружение venv
```
python -m venv venv
```

Aктивировать виртуальное окружение venv
```
 venv/Scripts/activate
```

Обновить менеджер пакетов pip
```
python3 -m pip install --upgrade pip
```

Установить зависимости из файла requirements.txt
```
pip install -r requirements.txt
```

Выполнить миграции
```
python3 manage.py migrate
```

Создать суперпользователя
```
python3 manage.py createsuperuser
```

Запустить проект
```
python3 manage.py runserver
```
