# api_final

### Описание:

API для проекта Yatube
Проект Yatube является социальной сетью, где любой пользователь может просматривать записи интересующей группы или автора. Авторизованные пользователи могут создавать собственные посты, подписываться на других авторов и оставлять комментарии к записям. Изменять или удалять записи может только автор. Посты пользователей могут быть разделены по группам.

### Технологии:

Python 3.7, Django 2.2, DRF, JWT

### Как запустить проект:

Клонируй репозиторий и перейди в него в командной строке:

```bash
cd api_final_yatube
```

Cоздай и активируй виртуальное окружение:

```bash
python -m venv venv
```

* Если у тебя Linux/macOS

    ```bash
    source venv/bin/activate
    ```

* Если у тебя windows

    ```bash
    source venv/scripts/activate
    ```

Установи зависимости из файла requirements.txt:

```bash
python -m pip install --upgrade pip
```

```bash
pip install -r requirements.txt
```

Выполни миграции:

```bash
python manage.py migrate
```

Запусти проект:

```bash
python manage.py runserver
```

### Автор:

[Беломоина Камила]
