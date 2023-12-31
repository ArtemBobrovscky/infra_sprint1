# Kittygram - социальная сеть на самых минималках для размещение фотографий котиков. Учебный проект Яндекс.Практикум.

# Описание проекта
Проект написан в рамках учебного курса по Python от Яндекс.Практикум.
Пользователи могут регистрироваться, загружать фотографии своих котов с кратким описанием, и смотреть котиков других пользователей. Основная задача  - обучение деплою проекта на сервер.

# Технологии

 - Python 3.9
 - Django==3.2.3
 - djangorestframework==3.12.4
 - Nginx
 - gunicorn
 
# Установка проекта на локальный компьютер из репозитория 
 - Клонировать репозиторий `git clone git@github.com:ArtemBobrovscky/infra_sprint1.git`
 - перейти в директорию с клонированным репозиторием
 - установить виртуальное окружение `python3 -m venv venv`
 - установить зависимости `pip install -r requirements.txt`
 - выполнить миграции `python3 manage.py migrate`
 - в директории /backend/kittygram_backend/ создать файл .env
 - в файле .env прописать ваш SECRET_KEY в виде: `SECRET_KEY = '<ваш_ключ>'`

# Примеры запросов к API

## Главная

```https://kittygramart.sytes.net/```

##  Добавление котика

```https://kittygramart.sytes.net/cats/add~```

## Страница котика

```https://kittygramart.sytes.net/cats/5```


# Автор
ArtemBobrovscky - [GitHub](https://github.com/ArtemBobrovscky)





