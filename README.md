# Velox API

A lightweight REST API built with FastAPI

![Python](https://img.shields.io/badge/Python-3.11%2B-3776ab?logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-0.111-009688?logo=fastapi&logoColor=white)
![License](https://img.shields.io/badge/License-MIT-blue)

---

A minimal REST API for user authentication and resource management. No unnecessary dependencies, no bloat.

## Installation

```bash
git clone https://github.com/yourname/velox-api.git
cd velox-api
pip install -r requirements.txt
uvicorn app.main:app --reload
```

API runs at `http://localhost:8000` · Docs at `/docs`

## Endpoints

| Method | Endpoint | Description |
|--------|----------|-------------|
| POST | `/auth/login` | Obtain JWT token |
| GET | `/users/me` | Get current user |
| GET | `/items/{id}` | Retrieve item |
| POST | `/items` | Create item |
