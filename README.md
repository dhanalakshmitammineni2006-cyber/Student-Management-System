🎓 Student Management System
A simple Student Management System built using Flask and SQLite with user authentication and CRUD operations.
Features
  Register & Login
  Add Student
  View Students
  Edit Student
  Delete Student
  API Endpoint → /api/students
  Modern Responsive UI
Tech Stack
  Python
  Flask
  SQLite
  HTML & CSS
I)How to Run
1️.Create Virtual Environment
  python -m venv venv
Activate it:
  venv\Scripts\activate
2️.Install Flask
pip install flask
3.Run App
  python app.py
4.Open in browser:
  http://127.0.0.1:5000/
5.PROJECT STRUCTURE:
Student-Management-System/
│
├── static/
│   └── style.css
│
├── templates/
│   ├── index.html
│   ├── view.html
│   ├── edit.html
│   ├── login.html
│   └── register.html
│
├── students.db
├── app.py
├── requirements.txt
└── .gitignore
II)Push Project to GitHub
    1️.Initialize Git
          git init
    2.Add Files
          git add .
    3️.Commit
          git commit -m "Initial commit"
    4️.Create Repository on GitHub
          Go to https://github.com
          Click New Repository
          Copy the repository URL
    5️.Connect Local Project to GitHub
          git remote add origin https://github.com/your-username/student-management-system.git
    6️.Push to GitHub
          git branch -M main
          git push -u origin main
