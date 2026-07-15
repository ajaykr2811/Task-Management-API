# TaskFlow API

A production-style Task Management Backend built with FastAPI and PostgreSQL.

## Tech Stack

- Python 3.12+
- FastAPI
- PostgreSQL
- SQLAlchemy
- Alembic
- JWT Authentication
- Docker
- Pytest

## Features

- User Authentication (JWT)
- Project Management
- Task Management
- Role-Based Access Control (RBAC)
- Search, Filter & Pagination
- Database Migrations
- RESTful APIs

## Project Structure

```
app/
api/
models/
schemas/
services/
repositories/
db/
core/
tests/
```

## Getting Started

### Clone Repository

```bash
git clone <repo-url>
cd taskflow-api
```

### Create Virtual Environment

```bash
python -m venv venv
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Run Application

```bash
uvicorn app.main:app --reload
```

API Documentation:

```
http://127.0.0.1:8000/docs
```
taskflow-api/
│
├── app/
│   ├── api/
│   ├── core/
│   ├── db/
│   ├── models/
│   ├── schemas/
│   ├── services/
│   ├── repositories/
│   ├── utils/
│   ├── dependencies/
│   ├── middleware/
│   └── main.py
│
├── migrations/
├── tests/
│
├── .env
├── .env.example
├── .gitignore
├── requirements.txt
├── alembic.ini
└── README.md

## License

MIT