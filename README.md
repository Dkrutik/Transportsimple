# Transport-Simple - Django Project

A simple Quora-like platform built using Django where users can:
- Register / Login
- Post Questions
- Answer Questions
- Like Answers
- Logout

---

## 🚀 Setup Instructions

### 1. Clone the Repository

bash
git clone https://github.com/your-username/Transportsimple.git
cd Transportsimple
 Create & Activate Virtual Environment:
python -m venv venv
venv\Scripts\activate  # On Windows
# OR
source venv/bin/activate  # On macOS/Linux
Install Requirements:- 
pip install -r requirements.txt
If requirements.txt is missing, install Django:
pip install django
Apply Migrations:
python manage.py makemigrations
python manage.py migrate
Run the Development Server:
python manage.py runserver
Then open your browser and go to:
http://127.0.0.1:8000/

🔐 Features
✅ Register
Visit /register/ to create a new user account.

✅ Login
Visit /login/ to access your account.

✅ Home Page
Shows all questions posted by users.

✅ Post a Question
After logging in, click "Ask Question" to post a question.

✅ Answer a Question
View any question to add your answer (if logged in).

✅ Like an Answer
Click the “Like” link to like an answer.

✅ Logout
Click the "Logout" link in the navigation bar.


Folder Structure: 

Transportsimple/
│
├── core/               # Django app with views, models, templates
│   ├── templates/core/ # HTML files
│   ├── views.py
│   ├── models.py
│   ├── forms.py
│   └── urls.py
│
├── Transportsimple/    # Django project settings
│   ├── settings.py
│   └── urls.py
│
├── db.sqlite3          # Default SQLite database
├── manage.py
└── requirements.txt

Screenshots:
![Screenshot 2025-04-09 100908](https://github.com/user-attachments/assets/cd763139-71aa-45d7-b5ac-829779d2844e)
![Screenshot 2025-04-09 100859](https://github.com/user-attachments/assets/72ca539d-4fae-4a7e-b1a4-d5bc4296d8c2)
![Screenshot 2025-04-09 100841](https://github.com/user-attachments/assets/bec2fb85-65a1-4451-b88d-136b3e129884)
![Screenshot 2025-04-09 100825](https://github.com/user-attachments/assets/9f9ef4db-f3dd-4c2d-ba29-e3e0f3ff4967)
![Screenshot 2025-04-09 100812](https://github.com/user-attachments/assets/84ef98a5-c867-4747-abca-151b863a2ec8)







