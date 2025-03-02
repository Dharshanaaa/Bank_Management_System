
# Loan Management System

### Description

The Loan Management System is a full-stack web application designed to streamline loan processing, tracking, and management. It provides a user-friendly interface for borrowers and administrators to handle loan applications and payments efficiently.
## Setup Instructions

### Clone Repository

```sh
git clone https://github.com/Dharshanaaa/Loan_Management_System.git
cd Loan_Management_System
```

### Backend Setup

```sh
python -m venv venv
source venv/bin/activate  # macOS/Linux
venv\Scripts\activate  # Windows
pip install -r requirements.txt
```

Create a `.env` file in the project root:

```ini
API_KEY=your_brevo_api_key
DB_HOST=your_database_host
DB_NAME=your_database_name
DB_USER=your_database_user
DB_PASSWORD=your_database_password
DB_PORT=5432
```

Run migrations and start server:

```sh
python manage.py makemigrations
python manage.py migrate
python manage.py runserver
```

API runs at: [http://127.0.0.1:8000/](http://127.0.0.1:8000/)

### Frontend Setup

```sh
cd frontend
npm install
npm run dev
```

Frontend runs at: [http://localhost:5173/](http://localhost:5173/)
