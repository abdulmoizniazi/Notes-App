# Notes App

## Overview
Notes App is a simple and efficient note-taking application built with a modern tech stack. The frontend is developed using **Vite**, while the backend is powered by **Django** with **SQLite** as the database.

## Features
- Create, read, update, and delete notes
- User-friendly and fast UI with Vite
- Secure and scalable backend using Django
- Persistent data storage with SQLite

## Tech Stack
### Frontend:
- **Vite** (React/JavaScript framework for fast development)

### Backend:
- **Django** (Python-based web framework)
- **SQLite** (Lightweight database for local storage)

## Installation

### Backend Setup (Django)
1. Clone the repository:
   ```bash
   git clone https://github.com/abdulmoizniazi/Notes-App.git
   cd Notes-App/backend
   ```
2. Create and activate a virtual environment:
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   ```
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. Apply migrations and start the server:
   ```bash
   python manage.py migrate
   python manage.py runserver
   ```

### Frontend Setup (Vite)
1. Navigate to the frontend directory:
   ```bash
   cd ../frontend
   ```
2. Install dependencies:
   ```bash
   npm install
   ```
3. Start the development server:
   ```bash
   npm run dev
   ```

## Usage
- Open your browser and visit `http://localhost:5173` to access the frontend.
- The backend API runs at `http://127.0.0.1:8000`.

## Contributions
Contributions are welcome! Feel free to open issues and submit pull requests.

## Contact
For any inquiries, contact: [abdulmoizniazi@gmail.com](mailto:abdulmoizniazi@gmail.com)

## License
This project is licensed under the MIT License.


This is Awesome... Made with ❤️ by Moiz
