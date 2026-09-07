# Blog Application

A full-stack blog application built with **Python and Django** that allows authenticated users to create, view, edit, and delete blog posts. The application includes user registration and authentication, image uploads, post search, ownership-based authorization, and a responsive interface built with HTML, CSS, and Bootstrap.

## Features

* User registration and authentication
* Create, view, edit, and delete blog posts
* Users can edit or delete only their own posts
* Search posts by text or username
* Optional image uploads for posts
* Newest posts displayed first
* Form validation using Django Forms
* Django ORM for database operations
* Responsive user interface using Bootstrap
* Login-required access for post management

## Technologies Used

* **Python**
* **Django**
* **HTML**
* **CSS**
* **Bootstrap**
* **SQLite**
* **Git & GitHub**

## Project Structure

```text
chaiheadq/
├── chaiheadq/
│   ├── settings.py
│   ├── urls.py
│   ├── asgi.py
│   └── wsgi.py
├── tweet/
│   ├── migrations/
│   ├── templates/
│   ├── forms.py
│   ├── models.py
│   ├── urls.py
│   └── views.py
├── manage.py
└── requirements.txt
```

## How to Run Locally

### 1. Clone the repository

```bash
git clone https://github.com/sadikshya63/Blog-Application.git
cd Blog-Application
```

### 2. Create and activate a virtual environment

On Windows:

```bash
python -m venv myenv
myenv\Scripts\activate
```

### 3. Install dependencies

```bash
pip install -r chaiheadq/requirements.txt
```

### 4. Run migrations

```bash
cd chaiheadq
python manage.py migrate
```

### 5. Start the development server

```bash
python manage.py runserver
```

Open `http://127.0.0.1:8000/` in your browser.

## Future Improvements

* Add comments and likes
* Add user profile pages
* Add pagination
* Add REST API functionality
* Improve deployment and production configuration

## Author

**Sadikshya Niroula**

* GitHub: https://github.com/sadikshya63
* LinkedIn: https://www.linkedin.com/in/sadikshya-niroula-48317b3ab/
