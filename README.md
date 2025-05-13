# Django_blog

Простой блог, разработанный на Django. Поддерживает регистрацию, вход пользователей и создание постов через админку или веб-интерфейс.

# 🔧 Функционал
Просмотр всех постов на главной странице
Просмотр детальной информации по каждому посту
Создание постов (доступно только авторизованным пользователям)
Авторизация и выход из системы
Админ-панель Django для управления контентом

# 🚀 Установка
```
git clone https://github.com/USERNAME/REPOSITORY.git
cd REPOSITORY
```
-
Создать виртуальное окружение и установить зависимости:

```
python -m venv venv
source venv/bin/activate    # Для Linux/macOS
venv\Scripts\activate.bat   # Для Windows

pip install -r requirements.txt
```
-
Применить миграции и запустить сервер:

```
python manage.py migrate
python manage.py runserver
```
-
Создать суперпользователя (опционально):
```
python manage.py createsuperuser
```
-
# 📁 Структура проекта
```
myblog/
│
├── blog/              # Приложение блога
│   ├── templates/
│   │   └── blog/
│   │       ├── index.html
│   │       ├── post_detail.html
│   │       └── create_post.html
│   ├── views.py
│   ├── models.py
│   └── forms.py
│
├── templates/
│   └── login.html
│
├── db.sqlite3
└── manage.py
```

# ✅ Используемые технологии
Python 3.x
Django 5.x
HTML/CSS (шаблоны Django)

# 📌 Заметки

Проект предназначен для обучения и разработки, не используйте как есть в продакшене
Адрес входа в админку: /admin/
Страница входа: /login/
Страница создания поста: /create/ (только для авторизованных)
