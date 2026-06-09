# Dockerized Web App

This is a hands-on DevOps project to demonstrate containerization using Docker.

**Tech Stack**: Docker, Nginx, Linux, Git

**What I did**:
1. Created `Dockerfile` to define a custom Nginx image
2. Built the Docker image using `docker build` command
3. Ran the web application inside a Docker container using `docker run`
4. Exposed port 80 to access the app in browser

**Key Learning**: 
- Writing Dockerfiles
- Container lifecycle: build, run, stop
- Benefits of containerization for consistent deployment

**How to run**:
1. `docker build -t nazmeen-webapp .`
2. `docker run -d -p 80:80 nazmeen-webapp`
3. Open `localhost` in browser# dockerized-web-app
Containerized a web application using Docker. Wrote Dockerfile, built custom image, and ran Nginx container. Demonstrates understanding of containerization, Docker commands, and Linux basics.
