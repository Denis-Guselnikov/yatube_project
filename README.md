## Учебный проект Yatube - Социальная сеть блогеров.
Разработан в рамках обучения по программе "Python WEB разработчик" в Яндекс.Практикум.

# В проекте реализованы следующие функции:
- Создание сообщества для публикаций.
- Публикация поста в ленте, (возможность выбора группы, в которой появится этот пост);
- Добавление новых записей авторизованными пользователями;
- Добавление фотографий;
- Добавление и редактирование комментариев;
- Редактирование постов только его автором;
- Подписка/отписка на понравившихся авторов;
- Создание отдельной ленты с постами авторов на которых подписан пользователь;
- Реализовано кэширование, работает на главной странице;
- Работает пагинация;

# Стек технологий.
- Python3
- Django
- Pytest
- Pillow
- Bootstrap

# Запуск приложения.
- Установите зависимости из requirements.txt:

pip install -r requirements.txt

- Выполните все необходимые миграции:

python manage.py makemigrations

python manage.py migrate

- Для доступа к панели администратора создайте администратора:

python manage.py createsuperuser

- Запустите приложение:

python manage.py runserver