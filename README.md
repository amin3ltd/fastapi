# 🦄 FastAPI Projects — From the Book *"Building FastAPI Web APIs with Python"*

This repository contains multiple projects built step-by-step while reading the book **"Building FastAPI Web APIs with Python"**. These projects are designed to help developers master **FastAPI**, a modern, high-performance web framework for building APIs with Python 3.7+.

## 📘 Book Overview

The book teaches FastAPI by guiding you through real-world examples including:

- Creating APIs
- Database integration (SQLAlchemy + SQLite/PostgreSQL)
- JWT-based authentication
- Background tasks
- Dependency injection
- Pydantic for validation
- Async/await best practices

## 🗂️ Projects Included

### 1. 📦 **Todo API**
A simple task management API to perform CRUD operations.
- Concepts: Routing, Dependency Injection, Pydantic models
- Endpoints: Create, Read, Update, Delete todos

### 2. 🔐 **Auth API**
Implements authentication using OAuth2 and JWT tokens.
- Concepts: User login/signup, token generation, password hashing
- Features: Role-based access control

### 3. 🧠 **Blog API**
A complete blog system with database integration.
- Concepts: SQLAlchemy ORM, Alembic migrations
- Features: Posts, Comments, Relationships, Users

### 4. 🛠 **Background Tasks API**
Demonstrates background task execution.
- Use Case: Sending email confirmations after user registration
- Concepts: FastAPI’s `BackgroundTasks`, async jobs

### 5. 📡 **Async External API Calls**
Working with third-party APIs asynchronously.
- Tools: `httpx` for making non-blocking HTTP requests

---

## 🚀 Getting Started

### 🔧 Requirements

- Python 3.8+
- Poetry or pip
- Virtualenv (optional)
- PostgreSQL or SQLite (depending on the project)

### ⏳ Installation

```bash
# Clone the repo
git clone https://github.com/amin3ltd/fastapi.git
cd fastapi-book-projects

# Navigate to a project
cd todo-api

# Install dependencies
pip install -r requirements.txt

# Run the app
uvicorn main:app --reload
