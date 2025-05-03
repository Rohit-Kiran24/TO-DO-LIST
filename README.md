# Task Smash - Modern To-Do List Application

A beautiful, responsive To-Do List application built with Flask and SQLAlchemy.

![Task Smash Screenshot](screenshot.png)

## Features

- Modern, responsive UI
- Add, edit, and delete tasks
- Persistent storage with SQLite
- Beautiful animations and transitions
- Mobile-friendly design

## Local Development

1. Clone the repository:
```bash
git clone https://github.com/Rohit-Kiran24/TO-DO-LIST.git
cd TO-DO-LIST
```

2. Create a virtual environment:
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

3. Install dependencies:
```bash
pip install -r requirements.txt
```

4. Run the application:
```bash
python app.py
```

5. Open your browser and visit `http://localhost:5000`

## Deployment

This application is configured for easy deployment to Render.com:

1. Sign up for a free account at [Render.com](https://render.com)
2. Connect your GitHub repository
3. Create a new Web Service
4. Select your repository
5. Use the following settings:
   - Environment: Python
   - Build Command: `pip install -r requirements.txt`
   - Start Command: `gunicorn app:app`
6. Click "Create Web Service"

Your application will be automatically deployed and you'll get a public URL.

## Technologies Used

- Flask
- SQLAlchemy
- HTML5
- CSS3
- Font Awesome
- Gunicorn

## License

MIT License 