# Music-WebApp


**Описание:**

Music-WebApp - это веб-приложение, созданное с использованием Django, которое позволяет вам слушать музыку.

**Установка:**

1. **Установите Pipenv:**

```
pip install pipenv
```

2. **Перейдите в папку проекта:**

```
cd MusicApp
```

3. **Создайте виртуальную среду и активируйте ее:**

```
pipenv install
pipenv shell
```

4. **Запустите сервер Django:**

```
python manage.py runserver
```

**Доступ к приложению:**

- Откройте браузер и перейдите по адресу `http://127.0.0.1:8000`.
- Вы должны увидеть главную страницу приложения.

**Функциональность:**

- **Просмотр списка песен:**
    - На главной странице отображается список всех доступных песен.
    - Вы можете фильтровать песни по исполнителю, жанру или названию.
- **Прослушивание песен:**
    - Вы можете прослушать любую песню, нажав на ее название.
    - Во время прослушивания песни вы можете регулировать громкость и переключаться на другие песни.

**Структура проекта:**

- `Pipfile`: Файл, который содержит список зависимостей проекта.
- `MusicApp`: Папка, которая содержит код Django.
- `manage.py`: Файл, который используется для управления сервером Django.

**Запуск приложения:**

1. **Убедитесь, что у вас установлен Pipenv.**
2. **Перейдите в папку проекта.**
3. **Активируйте виртуальную среду.**
4. **Запустите сервер Django.**
