# CO3001 Tutor Support System

## Overview
**CO3001 Tutor Support System** is a web-based application designed to support interactions between **Students** and **Tutors**.  
This project was developed as part of the *CO3001 – Software Engineering* course at Ho Chi Minh City University of Technology (HCMUT).

The system allows users to register accounts, browse tutors, schedule tutoring sessions, manage learning activities, and provide feedback after sessions.

---

## Objectives
- Provide a platform for students to easily find suitable tutors  
- Support scheduling and management of tutoring sessions  
- Enable feedback and evaluation of tutors  
- Apply software engineering principles in a real-world project

---

## echnologies Used

| Component  | Technology |
|-----------|------------|
| Backend   | Python, Django |
| Frontend  | HTML, CSS, Django Templates |
| Database  | SQLite |
| Framework | Django (MVC pattern) |
| Tools     | Git, GitHub |

---

## Project Structure

```

├── accounts/                 # User authentication and authorization
├── students/                 # Student-related features
├── tutors/                   # Tutor-related features
├── tutoring_sessions/        # Tutoring session management
├── templates/                # HTML templates
├── static/                   # Static files (CSS, images)
├── manage.py                 # Django management script
└── db.sqlite3                # SQLite database

````

---

## Installation and Run

### 1. Clone the repository
```bash
git clone https://github.com/Winuim12/CO3001_TutorSupportSystem.git
cd CO3001_TutorSupportSystem
````

### 2. Create a virtual environment (recommended)

```bash
python -m venv venv
source venv/bin/activate      # macOS / Linux
venv\Scripts\activate         # Windows
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

### 4. Apply migrations and run the server

```bash
python manage.py migrate
python manage.py runserver
```

### 5. Open the application

Visit the following URL in your browser:

```
http://127.0.0.1:8000/
```

---

## Main Features

### Authentication

* User registration (Student / Tutor)
* Login & logout
* Account management

### Student Features

* View tutor list
* Search tutors
* Book tutoring sessions
* View session history

### Tutor Features

* Manage availability
* Accept or reject tutoring sessions
* View assigned students
* Receive feedback

### Feedback & Management

* Rate tutors after sessions
* Track tutoring sessions

---

## Future Improvements

* Implement RESTful APIs
* Advanced tutor filtering (subjects, price, ratings)
* Email / notification system
* Frontend framework integration (React / Vue)
* Automated testing (unit & integration tests)

---

## Authors

**CO3001 Project Team**
Ho Chi Minh City University of Technology – VNU-HCM

Course: CO3001 – Software Engineering

---

## License

This project is developed for **educational purposes only**.
