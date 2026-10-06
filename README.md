# Django Blog Project

A basic blog web application built with Django while learning the Django framework through a YouTube tutorial.

This project was created as a hands-on learning project to understand the fundamentals of Django and how different parts of a Django application work together.

## About the Project

I built this project while learning Django through a YouTube tutorial.

The main purpose of the project was to get practical experience with Django by building a simple web application instead of only learning the concepts theoretically.

Through this project, I learned about Django's project structure, applications, URLs, views, templates, models, databases, and media files.

## Technologies Used

- Python
- Django
- HTML
- CSS
- SQLite
- Git
- GitHub

## Django Concepts Practiced

- Django project structure
- Django applications
- URL routing
- Views
- Templates
- Models
- Database integration
- SQLite database
- Static and media files
- Django development server
- Managing dependencies using `requirements.txt`

## Project Structure

```text
Blog-project/
│
├── blog/
│   └── Django project configuration
│
├── myapp/
│   └── Django application
│
├── templates/
│   └── HTML templates
│
├── media/
│   └── Uploaded media files
│
├── db.sqlite3
├── manage.py
├── requirements.txt
├── .gitignore
└── .gitattributes
```

## How Django Works in This Project

The basic flow of a Django application can be understood as:

```text
User
  ↓
URL
  ↓
View
  ↓
Model / Database
  ↓
Template
  ↓
Web Page
```

The user sends a request to the application.

Django uses URL routing to determine which view should handle the request. The view processes the request and can interact with the database through models. Finally, the required information is passed to a template and displayed as a web page.

## Installation

### 1. Clone the Repository

```bash
git clone https://github.com/suramaxi92/Blog-project.git
```

### 2. Navigate to the Project Folder

```bash
cd Blog-project
```

### 3. Create a Virtual Environment

```bash
python -m venv venv
```

### 4. Activate the Virtual Environment

**Windows:**

```bash
venv\Scripts\activate
```

**macOS / Linux:**

```bash
source venv/bin/activate
```

### 5. Install the Required Packages

```bash
pip install -r requirements.txt
```

### 6. Run the Development Server

```bash
python manage.py runserver
```

### 7. Open the Application

Open the following URL in your browser:

```text
http://127.0.0.1:8000/
```

## Learning Objectives

The main goal of this project was to learn the fundamentals of Django and understand how a basic Django web application is developed.

By building this project, I gained hands-on experience with:

- Creating a Django project
- Creating Django applications
- Connecting URLs with views
- Working with HTML templates
- Working with models and databases
- Managing media files
- Running a Django application locally

## What I Learned

This project helped me understand the basic workflow of Django and how the different components of a web application are connected.

It also gave me practical experience in building a web application using Python and Django rather than only studying the framework theoretically.

## Future Improvements

As I continue learning Django, I plan to improve this project by adding features such as:

- User authentication
- User registration and login
- Comments
- Search functionality
- Post categories
- Pagination
- Improved UI/UX
- Deployment

## Project Status

This is a **learning project** created while following a Django tutorial.

It is mainly intended to practice and understand the fundamentals of the Django framework.

## Author

**Surendar B**

GitHub:  
https://github.com/suramaxi92

LinkedIn:  
https://www.linkedin.com/in/surendar-b-636538291

## Acknowledgement

This project was built by following a YouTube tutorial as part of my learning journey with the Django framework.

The project was used to gain hands-on experience and understand the fundamentals of Django web development.

## License

This project is created for learning and educational purposes.
