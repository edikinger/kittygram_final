<<<<<<< HEAD
Описание проекта
Kittygram — это социальная сеть, где пользователи могут:

Создавать профили

Загружать фотографии своих питомцев

Комментировать и лайкать посты других пользователей

Технологический стек
Backend:

Python 3.9+

Django REST Framework

PostgreSQL

Docker

Frontend:

React.js

Инфраструктура:

Docker Compose

GitHub Actions (CI/CD)

Nginx
=======
### Как запустить проект:

Клонировать репозиторий и перейти в него в командной строке:

```
git clone https://github.com/yandex-praktikum/kittygram.git
```

```
cd kittygram
```

Cоздать и активировать виртуальное окружение:

```
python3 -m venv env
```

```
source env/bin/activate
```

Установить зависимости из файла requirements.txt:

```
python3 -m pip install --upgrade pip
```

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
>>>>>>> ded96da74a8691e33446bfec6cffcb276a2c13b7
