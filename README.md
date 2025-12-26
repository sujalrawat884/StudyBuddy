# 📚 StudyBuddy – AI-Powered Student Learning Portal

StudyBuddy is an AI-powered web platform designed to help college students study smarter by providing **syllabus-aware assistance, previous year questions (PYQs), and learning resources** in one place.

Built as a personal project during my B.Tech, StudyBuddy focuses on **practical problem-solving using AI, backend engineering, and real-world deployment**.

---

## 🚀 Features

- 🤖 **AI Chatbot (Syllabus-Aware)**
  - Built using LangChain
  - Answers questions based on **year, subject, and unit**
- 🔐 **Authentication System**
  - Secure login & signup
  - Password hashing using **bcrypt**
- 📩 **Email OTP Verification**
  - Registration & password reset via **Gmail OTP**
  - Implemented using **Mailjet**
- 📚 **Academic Resources**
  - Previous Year Questions (PYQs)
  - Quantum notes & syllabus-wise materials
- 🌐 **Live Deployment**
  - Hosted on Render
  - Custom domain: **https://studybuddy.sujalrawat.tech**

---

## 🛠️ Tech Stack

### Backend
- **Python (Flask)**
- **PostgreSQL** (hosted)
- **LangChain** for AI chatbot logic
- **REST APIs**

### Frontend
- **HTML, CSS, JavaScript**
- Jinja2 templates

### Security & Auth
- **bcrypt** for password hashing
- **OTP-based email verification**

### Deployment
- **Render**
- **Heroku-style Procfile**
- Custom domain integration

---

## 📂 Project Structure

```text
StudyBuddy/
│
├── app.py               # Main Flask application
├── models.py            # Database models
├── chatbot/             # AI chatbot logic
├── resources/           # Study materials & PYQs
├── syllabus/             # Syllabus data
├── templates/           # HTML templates
├── static/              # CSS & JS files
├── requirements.txt     # Python dependencies
├── Procfile              # Deployment config
└── README.md
⚙️ Installation & Setup
1️⃣ Clone the repository

bash
Copy code
git clone https://github.com/sujalrawat884/StudyBuddy.git
cd StudyBuddy
2️⃣ Create a virtual environment

bash
Copy code
python -m venv venv
source venv/bin/activate  # Windows: venv\Scripts\activate
3️⃣ Install dependencies

bash
Copy code
pip install -r requirements.txt
4️⃣ Run the application

bash
Copy code
python app.py
