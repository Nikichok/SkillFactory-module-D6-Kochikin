# Развертывание приложения

1. Развернем виртуальное окружение (например: 'python -m venv C:\Users\Q\django_test')
2. Активируем ('C:\Users\Q\django_test\Scripts\activate.bat')
3. Скачиваем Джанго ('pip install Django==2.2.6')
4. Скачиваем Pillow ('pip install Pillow')
5. Копируем файлы из архива ()
6. Запускаем сервер (из родительского каталога командой 'python manage.py runserver')

#Теперь доступны следующие URL:

- http://127.0.0.1:8000/admin - Админка (user: admin, password: admin);
- http://127.0.0.1:8000/index - приветственная страница со списком книг (кнопками доступны слеедующие 4 URL);
- http://127.0.0.1:8000/authors - список авторов;
- http://127.0.0.1:8000/author/create - добавление автора;
- http://127.0.0.1:8000/author/create_many - добавление нескольких авторов;
- http://127.0.0.1:8000/author_book/create_many - добавление нескольких книг и авторов