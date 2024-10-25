# TODO LIST: Django + api
___
The TODO LIST project on Django using the API is a web application that allows users to manage their tasks.
___
### Developers (Juniors): 

<div id="header" align="center">
  <img src="https://media2.giphy.com/media/v1.Y2lkPTc5MGI3NjExdGVocXo0MzI3aHgyMnFoeHlocHE0cTlsdXdtdjFjbG5waDBkMWl0ciZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/ua7vVw9awZKWwLSYpW/giphy.gif" width="100"/>
</div>

<div id="links" align="left">
  <a href="https://t.me/FORREST_GOD">
    <img src="https://img.shields.io/badge/Володя-blue?logo=telegram&logoColor=white" alt="Володя" width="75"/>
</a>
</div>

#### функционал основного приложения (WEB)

<div id="links" align="left">
  <a href="https://t.me/zkvttn">
    <img src="https://img.shields.io/badge/Татьяна-blue?logo=telegram&logoColor=white" alt="Татьяна" width="75"/>
</a>
</div>

#### модели базы данных

<div id="links" align="left">
  <a href="https://t.me/dariandrr">
    <img src="https://img.shields.io/badge/Дарья-blue?logo=telegram&logoColor=white" alt="Дарья" width="75"/>
</a>
</div>

#### дизайн сайта + работа с jinja2

<div id="links" align="left">
  <a href="https://t.me/alonemooo">
    <img src="https://img.shields.io/badge/Антон-blue?logo=telegram&logoColor=white" alt="Антон" width="75"/>
</a>
</div>

#### api + контроль

# 💻 Tech Stack:

<div id="links" align="center">

![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54) 
![Django](https://img.shields.io/badge/django-%23092E20.svg?style=for-the-badge&logo=django&logoColor=white)
![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white) 
![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E) 
![SQLite](https://img.shields.io/badge/sqlite-%2307405e.svg?style=for-the-badge&logo=sqlite&logoColor=white) 

</div>

# Start project

```Python
1. python -m venv venv
2. venv\Scripts\activate
3. pip install -r req.txt
 ```

### Create new user (full admin)
```Python
python manage.py createsuperuser
 ```

### About project eng
1. Default auth django
   - Custom user 
   - Fields User: email, name, is_active, is_staff (admin), is_superuser (admin)
2. Database
   - default django db (sqlite3)
3. Plan for working with a to-do list:
   - The user adds a category, such as work, school, or miscellaneous (use get-post requests). 
   - Each category contains notes on the named topic. 
   - Notes should have priority (highlighted in different colors)
4. Docker (familiarization stage)
5. Jinja2 is used as a template engine
6. API (use drf)
7. Todo-list and API applications are different.  
   - to-do list: latest app (web)
   - API: for use on other devices

### About project ru
1. Аутентификация по умолчанию в Джанго
   - Усовершенственный пользователь (убраны не нужные поля с дефолтного django) 
   - Поля Пользователь: адрес электронной почты, имя, is_active, is_staff (администратор), is_superuser (администратор)
2. База данных
   - база данных django по умолчанию (sqlite3)
3. План работы со списком дел:
   - Пользователь добавляет категорию, например «работа», «учеба» или «разное» (используйте запросы get-post).  
   - Каждая категория содержит заметки по названной теме.  
   - Заметки должны иметь приоритет (выделены разными цветами)
4. Docker (этап ознакомления)
5. Jinja2 используется в качестве шаблонизатора.
6. API (используется drf)
7. Приложения todo-list и api разделены между собой.  
   - todo-list: основное приложение (web)
   - api: для использования на других устройствах







