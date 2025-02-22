# FastAPI Todo

A modern full-stack todo application built with FastAPI (backend) and React (frontend), designed to manage tasks efficiently.

<p align="center">
    <img src="https://img.shields.io/github/license/YashwanthKothakota9/fastapi-todo?style=flat-square&logo=opensourceinitiative&logoColor=white&color=0080ff" alt="license">
    <img src="https://img.shields.io/github/last-commit/YashwanthKothakota9/fastapi-todo?style=flat-square&logo=git&logoColor=white&color=0080ff" alt="last-commit">
    <img src="https://img.shields.io/github/languages/top/YashwanthKothakota9/fastapi-todo?style=flat-square&color=0080ff" alt="top-language">
    <img src="https://img.shields.io/github/languages/count/YashwanthKothakota9/fastapi-todo?style=flat-square&color=0080ff" alt="language-count">
</p>

---

## Table of Contents

- [FastAPI Todo](#fastapi-todo)
  - [Table of Contents](#table-of-contents)
  - [Overview](#overview)
  - [Features](#features)
  - [Project Structure](#project-structure)
  - [Getting Started](#getting-started)
    - [Prerequisites](#prerequisites)
    - [Installation](#installation)
    - [Acknowledgments](#acknowledgments)

---

## Overview

FastAPI Todo is a full-stack application that combines a high-performance FastAPI backend with a responsive React frontend. It allows users to create, manage, and track todo lists seamlessly, leveraging modern web technologies and containerization for deployment.

---

## Features

- Create, read, update, and delete (CRUD) todo items and lists.
- RESTful API powered by FastAPI for efficient backend operations.
- Intuitive and responsive React-based user interface.
- Dockerized services for easy deployment and scalability.
- Nginx integration for serving the frontend and proxying API requests.

---

## Project Structure

fastapi-todo/
├── README.md              # Project documentation
├── backend/               # FastAPI backend
│   ├── Dockerfile         # Docker configuration for backend
│   ├── pyproject.toml     # Python project metadata
│   ├── requirements.txt   # Python dependencies
│   └── src/               # Backend source code
├── frontend/              # React frontend
│   ├── package.json       # Node.js dependencies and scripts
│   ├── public/            # Static assets
│   └── src/               # React source code
├── docker-compose.yml     # Multi-container orchestration
└── nginx/                 # Nginx configuration
    └── nginx.conf         # Nginx server settings



---

## Getting Started

### Prerequisites

Ensure your environment meets the following requirements:
- **Python 3.9+** (for backend)
- **Node.js 16+** and **npm** (for frontend)
- **Docker** and **Docker Compose** (for containerized setup)

### Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/YashwanthKothakota9/fastapi-todo.git
   cd fastapi-todo
   
2. **Install Dependencies:**
   - Backend(Python)
      ```bash
      cd backend
      pip install -r requirements.txt
      cd ..
   - Frontend (Node.js):
        ```bash
        cd frontend
        npm install
        cd ..
3. **Build With Docker:**
    ```bash
        docker compose --build

----

### Acknowledgments

- [FastAPI](https://fastapi.tiangolo.com/) for the backend framework.
- [React](https://react.dev/) for the frontend library.
- [Docker](https://www.docker.com/) for containerization support.
