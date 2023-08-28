# Todo Application

Welcome to the Todo Application! This application uses React as the frontend, providing a user-friendly interface for managing tasks. The backend is built using the Django framework with Django REST framework (DRF), allowing seamless communication between the frontend and backend through API requests.

## Features

- Add new tasks with titles and descriptions.
- Mark tasks as completed or incomplete.
- Edit task details.
- Delete tasks from the list.
- Filter tasks by completion status.

## Technologies Used

- React: A JavaScript library for building user interfaces.
- Django: A high-level Python web framework.
- Django REST framework (DRF): A powerful toolkit for building Web APIs in Django.

## Getting Started

Follow these instructions to set up and run the Todo Application locally:

### Prerequisites

- Node.js: Ensure Node.js is installed on your system. You can download it from https://nodejs.org/.
- Python: Make sure you have Python 3.x installed on your system.

### Installation

1. Clone the repository:

```bash
git clone https://github.com/yourusername/todo-application.git
cd todo-application
```

2. Frontend Setup

```bash
cd frontend
npm install
```
3. Backend Setup
```bash
cd backend
pipenv install djangorestframework django-cors-headers
python manage.py runserver
```

4. Start the Development Servers:

- Frontend: In the `frontend` directory, run:

```bash
npm start
```
```bash
python manage.py runserver
```
5. Access the Application:

Open your web browser and go to `http://localhost:3000` to interact with the Todo Application.