Project Description: FastAPI Issue Tracker

This repository contains a functional Issue Tracker API developed following the "FastAPI Crash Course" by Traversy Media. The project focuses on building a high-performance backend using modern Python standards and the FastAPI framework.

Features & Technical Overview
Asynchronous API: Built on top of Starlette and Pydantic, leveraging Python’s type hints for automatic data validation and serialization.

Full CRUD Functionality:
Supports Create, Read, Update, and Delete operations for managing issues.

Pydantic Schemas:
Implementation of data models for request validation (Create/Update) and response formatting.

Interactive Documentation:
Automatic integration with Swagger UI (available at /docs), allowing for real-time API testing without external tools.

Custom Middleware:
Includes a timing middleware to measure and return request processing time via custom HTTP headers (X-Process-Time).

CORS Configuration:
Setup for Cross-Origin Resource Sharing to allow frontend integration.

Local Storage:
Data persistence managed through a JSON-based file system for simplicity and focus on framework fundamentals.

Tech Stack

- Language: Python 3.10+
- Framework: FastAPI
- Server: Uvicorn (ASGI)
- Validation: Pydantic
- Development Tools: Virtual Environments (venv), Pip

Project Structure<br>
main.py: Application entry point and router integration.<br>
/app/routes/: Contains modularized API endpoints.<br>
/app/schemas.py: Defines data models and Enums for status/priority.<br>
/app/storage.py: Logic for JSON data persistence.<br>
/app/middleware/: Custom logic for request/response processing.<br>

Implementation Notes<br>
During this project, I implemented professional development workflows, including the use of Python virtual environments and dependency management via requirements.txt. The API is designed to be scalable, demonstrating the transition from simple routes to a modular architecture using APIRouter.

Credits: https://www.youtube.com/watch?v=8TMQcRcBnW8 Traversy Media.
