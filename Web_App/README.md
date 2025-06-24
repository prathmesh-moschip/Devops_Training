# Simple Flask App in Docker

A minimal Flask web application, containerized using Docker. Ideal for learning, testing, or deploying simple web apps with ease.


##  Setup Instructions (Run with Docker)

###  Prerequisites  
- Docker installed on your system: [https://www.docker.com](https://www.docker.com)

###  Build the Docker Image

```bash
docker build -t flask-docker-app .
```

###  Run the Container

```bash
docker run -p 5000:5000 flask-docker-app
```

###  Access the Application  
Once the container is running, open your browser and visit:

```
http://localhost:5000
```

You should see:  
**"Hello from Flask inside Docker!"**


##  Project Structure


~/Desktop/Web_App/
├── app.py
├── requirements.txt
├── Dockerfile
└── README.md

