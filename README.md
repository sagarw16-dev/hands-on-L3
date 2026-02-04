# ITCS 6190/8190 - Hands-On L3: Docker Microservices

## Project Description
This project demonstrates how to use Docker to build a multi-container environment. It includes a Python Flask web application and a Redis database for counting page hits. I also practiced running a standalone PostgreSQL container.

## How to Run the Project
To run this application, follow these steps:

1. Open your terminal in the project folder.
2. Run the command:
   > `docker compose up --build`
3. Once the terminal shows it is running, open your browser and go to:
   > `http://localhost:8000`

## What I Learnt
* Docker Installation: Successfully set up Docker Desktop on my machine.
* Container Networking: Learned how Docker Compose allows two different containers (Web and Redis) to talk to each other.
* Troubleshooting: Identified intentional errors in the provided Python code and Docker configuration and fixed them to get the app running.
* PostgreSQL: Practiced running a database container independently using the `docker run` command.

## Error
I encountered the following errors during the hands-on, which were logged in the GitHub Issues tab:
* Python Syntax: Fixed the `import` statements in `app.py`.
* Path Error: Fixed the `flask` executable error in the `Dockerfile` by using `python -m flask`.

## Screenshots
### 1. Docker Desktop App
This screenshot shows the containers running successfully in the Docker Desktop dashboard.
![alt text](<WhatsApp Image 2026-02-03 at 19.13.49.jpeg>)

### 2. Application Output
This screenshot shows the "Hello World" message and the counter in the web browser.
![alt text](<WhatsApp Image 2026-02-03 at 19.13.10.jpeg>)