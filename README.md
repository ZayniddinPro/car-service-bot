# car-service-bot
Telegram Bot
This bot will work properly with the usage of these requirements:

1. Aiogram - install with (pip install -U aiogram) or (pipenv install aiogram). If your device in Linux you can use ( pacman -S python-aiogram).
2. Environs of Django and Python(environs=8.0.0)
3. Django=3.2.8 for installation use(pip3 install Django). For Admin Panel you should first of all install(django-admin startproject admin) and run your server with(python manage.py runserver), for the backend (python manage.py startapp), and for migrations(python manage.py makemigrations) and then also (python manage.py migrate)
4. How to run car service_bot:
6. python pip install -r requirements.txt (for installing all counted packages above)
7. You should write (python manage.py migrate) in terminal to run django and database and also from data/config.py
8. Don't forget to open new .env file and take new token from BotFather and add your ID from Jsonbot
