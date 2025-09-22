# Todo-Taskapp
Django To-Do App  A simple To-Do application built with Django where users can:  ✍️ Sign up  🔑 Log in / Log out  ➕ Add tasks  ✏️ Edit tasks  ❌ Delete tasks  ✅ Mark tasks as updated 
⚙️ Features
User authentication (signup, login, logout)
Task management (CRUD: Create, Read, Update, Delete)
Login required for accessing tasks
SQLite as database (default Django DB)
🛠️ File Structure (Important Parts)
todo-django/
│
├── manage.py
├── db.sqlite3
├── templates/
│   ├── signup.html
│   ├── login.html
│   ├── todo.html
│   └── edit_todo.html
│
├── static/
│   └── css/
│       └── index.css
│
├── your_project/          # Main Django project folder
│   ├── settings.py
│   ├── urls.py
│   └── ...
│
└── todo/                  # App folder
    ├── models.py
    ├── views.py
    ├── urls.py
    └── ...
    📂 Project Setup Instructions
1. Clone the Repository
git clone https://github.com/your-username/todo-django.git
cd todo-django
If you have the project as a .zip, extract it and open the folder in your editor (VS Code / PyCharm).

2. Create a Virtual Environment (recommended)
python -m venv venv
Activate the environment:
On Windows:venv\Scripts\activate
On macOS/Linux:source venv/bin/activate
3. Install Requirementspip install django
(If you add more dependencies, create a requirements.txt later.)
4. Database Migrations
Run the following commands to set up your database:
python manage.py makemigrations
python manage.py migrate
5. Run the Server
python manage.py runserver
Now open your browser and visit:
👉 http://127.0.0.1:8000/
