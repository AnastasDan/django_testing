# Тестирование проектов YaNote и YaNews

Проекты YaNote и YaNews протестированы на Unittest и Pytest соответственно.

## Стек технологий

Python, Django, Pytest, Unittest

## Как развернуть проект

Клонируем себе репозиторий:

```
git clone git@github.com:AnastasDan/django_testing.git
```

Переходим в директорию:

```
cd django_testing
```

Cоздаем и активируем виртуальное окружение:

* Если у вас Linux/MacOS:

    ```
    python3 -m venv venv
    ```

    ```
    source venv/bin/activate
    ```

* Если у вас Windows:

    ```
    python -m venv venv
    ```

    ```
    source venv/Scripts/activate
    ```

Устанавливаем зависимости из файла requirements.txt:

```
pip install -r requirements.txt
```

## Как запустить тесты

Переходим в директорию ya_news и запускаем Pytest:

```
cd ya_news

pytest
```

Переходим в директорию ya_note и запускаем тесты Unittest:

```
cd ya_note

python manage.py test
```

## Автор проекта

[Anastas Danielian](https://github.com/AnastasDan)