# PSUSphere

## Project Description

PSUSphere is a Django-based web application for managing student and student organization information. The system stores information about colleges, programs, organizations, students, and organization memberships.

## Features

* Manage Colleges
* Manage Programs
* Manage Organizations
* Manage Students
* Manage Organization Memberships
* Django Admin interface
* Search students, programs, organizations, and colleges
* Filter records in the Django Admin
* Generate initial data using Faker
* Manage student organization memberships

## Technologies Used

* Python
* Django
* Faker
* Git and GitHub

## Project Structure

```text
PSUSphere/
├── projectsite/
│   ├── manage.py
│   ├── projectsite/
│   └── studentorg/
├── README.md
├── requirements.txt
└── .gitignore
```

## How to Run

1. Activate the virtual environment.

```text
myenv\Scripts\activate
```

2. Go to the directory containing `manage.py`.

```text
cd PSUsphere\projectsite
```

3. Run the Django development server.
```text
python manage.py runserver
```

4. Open the website in your browser:
```text
http://127.0.0.1:8000/
```

5. To access the Django Admin:
```text
http://127.0.0.1:8000/admin/
```

## Authors
* Aaron John B. Sulleza
* Sean Reinmarc C. Broñola
