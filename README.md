# 🤖 AI Resume Parser
AI-powered resume parser built with Django and Docker that extracts candidate information from uploaded resumes.

## 🚀 Features
- Upload and parse resumes (PDF/DOCX)
- Extract name, email, phone, skills, education, experience
- View parsed data in the web interface
- Admin dashboard
- Dockerized for easy deployment

## 📝 How it Works
Upload resume from the browser.
Resume is parsed using Python + NLP.
Data is displayed and stored in the database.

## ⚙️ Getting Started
## 🔧 Prerequisites
- Python 3.8+
- Docker & Docker Compose

### 🐳 Run with Docker
     docker-compose up --build
## Run Locally Without Docker
# Create and activate virtual environment
     python -m venv venv
     venv\Scripts\activate on Windows
# Install dependencies
     pip install -r requirements.txt
# Run migrations
     python manage.py migrate
# Start server
     python manage.py runserver
