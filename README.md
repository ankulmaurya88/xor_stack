# 📝 Django MySQL CRUD App

This is a simple **CRUD web application** built using the **Django framework** and **MySQL database**. It allows you to Create, Read, Update, and Delete student records through a user-friendly web interface.

---

## 🔧 Features

- Create new student entries
- View list of all students
- Edit/update existing student details
- Delete student records
- Fully integrated with MySQL database

---

## 💻 Tech Stack

- **Backend:** Python, Django
- **Frontend:** HTML (Django Templates)
- **Database:** MySQL
- **ORM:** Django Models

---

## 📦 Requirements

Install dependencies using:

```bash
pip install -r requirements.txt
```

```
bash
python manage.py makemigrations
python manage.py migrate
```
```bash
python manage.py runserver

```

```bash
student_crud/
├── studentapp/
│   ├── migrations/
│   ├── templates/
│   │   ├── student_list.html
│   │   ├── student_form.html
│   │   └── student_confirm_delete.html
│   ├── __init__.py
│   ├── admin.py
│   ├── apps.py
│   ├── forms.py
│   ├── models.py
│   ├── urls.py
│   └── views.py
├── student_crud/
│   ├── __init__.py
│   ├── settings.py
│   ├── urls.py
│   └── wsgi.py
├── manage.py
├── requirements.txt
└── README.md

```

---
🙋‍♂️ Author
Ankul Maurya

