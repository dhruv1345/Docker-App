```markdown
# Dockerized Flask App

This is a simple Python Flask application that is Dockerized. It serves as a basic example of how to create a Flask app and containerize it using Docker.

## Prerequisites

Before running the app, make sure you have the following installed:

- Docker: [Install Docker](https://docs.docker.com/get-docker/)
- Python 3.x (for development and local testing)

## Features

- Simple Flask API that returns a "Hello, World!" message.
- Dockerized application for easy deployment and scaling.

## Getting Started

Follow these steps to get the app running on your local machine.

### 1. Clone the repository

```bash
git clone https://github.com/dhruv1345/Docker-App.git
cd Docker-App
```

### 2. Build the Docker image

Ensure that Docker is running, then build the Docker image using the following command:

```bash
docker build -t flask-docker-app .
```

### 3. Run the Docker container

Once the image is built, run the container using the following command:

```bash
docker run -p 5000:5000 flask-docker-app
```

This will start the Flask app in the Docker container and map port 5000 on your machine to port 5000 on the container.

### 4. Access the app

You can now access the app by opening your browser and navigating to:

```
http://localhost:5000
```

You should see the message: `Hello, World!`
```

This is now properly formatted with code blocks and numbered steps. You can directly copy this into your `README.md` file.
