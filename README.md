# Task Management API 📝

A simple RESTful API built using **Node.js** and **Express** to manage tasks. This API allows users to create, retrieve, update, and delete tasks. The tasks are stored in a **MongoDB Atlas** database.

## Table of Contents 📚

- [Features 🚀](#features-rocket)
- [Setup 🔧](#setup-)
- [Environment Variables 🌿](#environment-variables-)
- [API Endpoints 📡](#api-endpoints-)
- [Technologies 💻](#technologies-)
- [License 🔒](#license-)

## Features 🚀

- **GET** `/tasks`: Retrieve a list of all tasks.
- **POST** `/tasks`: Create a new task with title, description, and status.
- **PUT** `/tasks/:id`: Update an existing task by its ID.
- **DELETE** `/tasks/:id`: Delete a task by its ID.

## Setup 🔧

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/task-management-api.git
cd task-management-api
