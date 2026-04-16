# Portfolio Website

My portfolio website built using Django and Bootstrap CSS to showcase my skills, projects, and work.

##  Live Demo
🔗 [(https://my-portfolio-jerrycode.vercel.app/)](#)  

## Preview
<img width="1863" height="1025" alt="image" src="https://github.com/user-attachments/assets/5f842e9b-8d78-4ff7-abdc-4cee03dcee45" />

---

## Tech Stack

- **Backend:** Django  
- **Frontend:** HTML, CSS, Bootstrap  
- **Database:** SQLite (default Django DB) and Postgres (Production)

---

## Features

- Home section with resume download button  
- About section  
- Projects showcase  
- Contact section  
- Responsive design using Bootstrap  

---

## Installation & Setup

Follow these steps to run the project locally:

```bash
# Create virtual environment
python -m venv venv

# Activate virtual environment
# Windows
venv\Scripts\activate
# Mac/Linux
source venv/bin/activate

# Install dependencies
pip install -r requirements.txt

# Run migrations
python manage.py migrate

# Run server
python manage.py runserver
```

## Project Structure 
```bash
portfolio/
│
├── manage.py
├── requirements.txt
├── build.sh
├── vercel.json
│
├── portfolio/
│   ├── __init__.py
│   ├── asgi.py
│   ├── settings.py
│   ├── urls.py
│   └── wsgi.py
│
├── myapp/
│   ├── migrations/
│   │   └── __init__.py
│   │
│   ├── static/
│   │   ├── Resume.pdf
│   │   ├── favicon.png
│   │   └── myapp/
│   │       ├── css/
│   │       │   └── style.css
│   │       └── images/
│   │           ├── img1.png
│   │           ├── img2.png
│   │           ├── img3.png
│   │           └── profile.png
│   │
│   ├── templates/
│   │   └── myapp/
│   │       ├── base.html
│   │       ├── home.html
│   │       ├── about.html
│   │       ├── projects.html
│   │       └── contact.html
│   │
│   ├── __init__.py
│   ├── admin.py
│   ├── apps.py
│   ├── models.py
│   ├── tests.py
│   ├── urls.py
│   └── views.py
```
