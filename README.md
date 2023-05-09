# social-network-vktask
Профильное задание на вакансию "Python-разработчик"
# Installation
Для дальнейших действий понадобится установленный Python. При разработке использовался Python 3.9.13  
1. Клонировать/скачать репозиторий.  
2. Переместиться в папку проекта командой cd.  
3. Создать виртуальное окружение командой  
`python -m venv venv`
4. Установить необходимые зависимости командами  
Windows - `venv\Scripts\activate`
Linux/MacOS - `source my-project-env/bin/activate`
Далее  
`pip install -r requirements.txt`

5. Для создания БД:  
```
python manage.py makemigrations
python manage.py migrate
```
6. Для создания суперпользователя:  
`python manage.py createsuperuser`
7. Для запуска сервера:  
`python manage.py runserver`
8. В браузере открыть: http://127.0.0.1:8000/ , откроется проект.

