# Recipe API Project

A Django REST Framework API for managing recipes. Users can register, authenticate, and manage their recipes with JWT-based authentication.

---

## Features

- **User Authentication**
  - Register, Login, and Profile endpoints
  - JWT-based authentication
- **Recipes**
  - Create, Read, Update, Delete (CRUD) operations
  - Fields: `title`, `description`, `time_minutes`, `category`, `ingredients`, `instructions`
  - Recipes are linked to authenticated users
- **Categories & Ingredients**
  - Organize recipes by category
  - Store ingredients as a list or string

---

## Tech Stack

- Python 3.11+
- Django 4.x
- Django REST Framework
- Simple JWT for authentication
- SQLite (default, can be switched to PostgreSQL or MySQL)

---

## Getting Started

### Prerequisites

- Python 3.11+
- pip
- virtualenv (optional but recommended)

### Installation

1. Clone the repository:

```bash
git clone https://github.com/<your-username>/recipe_api_project.git
cd recipe_api_project
