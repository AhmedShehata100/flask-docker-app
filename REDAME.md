# Flask Redis Docker App

A simple web application built with **Flask** and **Redis**, containerized using **Docker Compose**.

## 📦 Project Structure

project/
├── app.py
├── requirements.txt
├── Dockerfile
├── docker-compose.yml
└── .gitignore


## 🚀 Features

- Python Flask web server
- Redis as a backend datastore
- Dockerized using Dockerfile and Docker Compose
- Hot reload for development

## 🐳 Running the Project with Docker

Make sure you have Docker and Docker Compose installed.

### 1. Build and run the containers:

docker-compose up --build

The Flask app will be accessible at:
👉 http://localhost:9000

### 2. Stopping the containers:
docker-compose down



### 🔧 Project Files
app.py – Main Flask application.

Dockerfile – Builds the Flask app image.

docker-compose.yml – Defines the Flask and Redis services.

requirements.txt – Python dependencies.

.gitignore – Files and folders ignored by Git.



### 📝 Requirements (for manual run)
If you want to run the app outside Docker:

python3 -m venv env
source env/bin/activate   # or env\Scripts\activate on Windows
pip install -r requirements.txt
python app.py

(https://www.linkedin.com/in/ahmed-shehata10/) | https://github.com/AhmedShehata100