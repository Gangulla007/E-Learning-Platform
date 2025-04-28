# E-Learning-Platform 📚🚀

An innovative full-stack e-learning platform offering live virtual classrooms, interactive quizzes, and personalized learning paths.

## Features
- 🧑‍🏫 Live Virtual Classrooms with WebRTC
- 🎯 Interactive Quizzes after each module
- 🛤 Personalized Learning Recommendations
- 🖥 Course Listing and Enrollment System
- 📈 User Progress Tracking
- 🔒 Secure Authentication (Login/Signup)
- 🛠 Admin Dashboard for Course Creation

## Tech Stack
- **Frontend**: React.js, Tailwind CSS (optional for styling)
- **Backend**: Django, Django REST Framework
- **Database**: PostgreSQL
- **Live Streaming**: WebRTC (Simple-Peer, Socket.io)
- **Authentication**: Django-Allauth / JWT Authentication

## Installation

### Prerequisites
- Node.js
- Python 3.x
- PostgreSQL

### Frontend Setup
```bash
cd frontend
npm install
npm start

cd backend
python3 -m venv env
source env/bin/activate
pip install -r requirements.txt
python manage.py migrate
python manage.py runserver
