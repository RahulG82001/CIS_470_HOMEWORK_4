This is a simple Python Flask web app. When you open it in a browser, it shows:
"Hello, World!"

The app is packaged using Docker, which means it can run the same way on any computer that has Docker installed.

Requirements:

Python 3

Docker

Project Files:

app.py – the main Python file with the Flask app

requirements.txt – lists the required Python packages

Dockerfile – instructions for building the Docker image

How to Run:

Open a terminal or command prompt.

Go to the project folder where your files are.

Run this command to build the Docker image:

docker build -t flask-docker .

After it's done, run this command to start the container:

docker run -p 5000:5000 flask-docker

Open your browser and go to:

http://localhost:5000

You should see:
Hello, World!