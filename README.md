Simple DevOps Project

Author: Snehal

A small demo project to learn DevOps basics like containerization, CI pipeline, and running a simple Flask app.

Tools Used:
Python
Flask
Docker

GitHub Actions

Git (GitHub)

How to Run the App
1. Run Locally
pip install -r requirements.txt
python app.py


Open:

http://127.0.0.1:8000

2. Run with Docker
docker build -t myapp .
docker run -p 8000:8000 myapp


Open:

http://localhost:8000

 CI Pipeline (GitHub Actions)

This project includes a simple CI workflow that installs Python packages and checks the code on every push.

 Why I Built This

I built this to learn DevOps and show my understanding of Flask + Docker + CI pipelines for job opportunities.

