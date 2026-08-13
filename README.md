# End-to-End DevOps Project

![DevOps](https://img.shields.io/badge/DevOps-Project-blue)
![AWS](https://img.shields.io/badge/AWS-EC2-orange)
![Docker](https://img.shields.io/badge/Docker-Containerization-blue)
![GitHub](https://img.shields.io/badge/GitHub-Version_Control-black)
![Linux](https://img.shields.io/badge/Linux-Server-green)

---

# Project Overview

This project demonstrates an **End-to-End DevOps workflow** by deploying a web application using modern DevOps tools and practices.

The project focuses on implementing a real-world deployment lifecycle starting from source code management to cloud deployment.

The main objective is to gain practical experience with:

- Version Control using Git & GitHub
- Linux Server Administration
- AWS Cloud Deployment
- Nginx Web Server Configuration
- Docker Containerization
- Docker Compose Management

---
## Project Architecture

The following architecture illustrates the complete deployment workflow of the project, from local development to AWS EC2 deployment using Docker and Docker Compose.

![DevOps Architecture](diagrams/architecture.png)

#  Features

- GitHub based source code management
- AWS EC2 cloud deployment
- Linux server configuration
- Nginx web server setup
- Docker container deployment
- Docker Compose service management
- Version controlled development workflow

---

# Tech Stack

| Technology | Purpose |
|------------|---------|
| Git | Version Control |
| GitHub | Source Code Repository |
| AWS EC2 | Cloud Infrastructure |
| Amazon Linux | Server Operating System |
| Nginx | Web Server |
| Docker | Containerization |
| Docker Compose | Container Management |
| HTML | Frontend Application |

---

#  Project Architecture

Developer
|
↓
Git & GitHub Repository
|
↓
AWS EC2 Instance
|
↓
Amazon Linux Server
|
↓
Nginx Web Server
|
↓
Docker Containers
|
↓
Live Application

---

#  Folder Structure


end-to-end-devops-project
│
├── index.html
│
├── docker-compose.yml
│
├── README.md
│
├── screenshots
│
└── .gitignore


---

#  Installation

## Step 1: Clone Repository

```bash
git clone https://github.com/Rajesh2005rs/end-to-end-devops-project.git

Move into project directory:

cd end-to-end-devops-project

 Docker Commands

Check Docker version:

docker --version

Build Docker image:

docker build -t devops-project .

Run Docker container:

docker run -d -p 80:80 devops-project

Check running containers:

docker ps

Stop container:

docker stop container_id

 Docker Compose

Docker Compose is used to manage application services.

Start services:

docker compose up -d

Check services:

docker compose ps

Stop services:

docker compose down

 Docker Hub

Docker images can be stored and managed using Docker Hub.

Docker workflow:

Dockerfile
      |
      ↓
Build Image
      |
      ↓
Tag Image
      |
      ↓
Push Image to Docker Hub

Commands:

docker login

docker tag image_name username/image_name

docker push username/image_name
 AWS EC2 Deployment
EC2 Setup

Steps performed:-

Created AWS EC2 Instance
Connected using SSH
Installed required packages
Configured Nginx Web Server
Deployed application

SSH Connection:-

ssh -i key.pem ec2-user@public-ip
Nginx Installation

Install Nginx:

sudo yum install nginx -y

Start service:

sudo systemctl start nginx

Enable on boot:

sudo systemctl enable nginx

```
##  Application Deployment:-

Application is deployed on an AWS EC2 instance using Nginx web server.

Deployment location:
/usr/share/nginx/html
The application files are hosted inside the Nginx default web root directory.

#  Project Screenshots

# 📸 Project Screenshots

### 01. GitHub Repository
![GitHub Repository](screenshots/01-github-repository.png)

### 02. AWS EC2 Instance
![AWS EC2 Instance](screenshots/02-aws-ec2-instance.png)

### 03. EC2 Terminal
![EC2 Terminal](screenshots/03-ec2-terminal.png)

### 04. Docker Images
![Docker Images](screenshots/04-docker-images.png)

### 05. Docker Containers
![Docker Containers](screenshots/05-docker-ps.png)

### 06. Docker Compose
![Docker Compose](screenshots/06-docker-compose-ps.png)

### 07. Website Running
![Website Running](screenshots/07-website-running.JPG)

### 08. Docker Hub Repository
![Docker Hub Repository](screenshots/08-dockerhub-repository.png)

### 09. Git Status
![Git Status](screenshots/09-git-status.png)

### 10. Project Structure
![Project Structure](screenshots/10-project-structure.png)

# Future Improvements

Planned enhancements:

Implement CI/CD Pipeline using Jenkins or GitHub Actions
Infrastructure Automation using Terraform
Container Orchestration using Kubernetes
Monitoring using Prometheus and Grafana
Add Automated Testing
 Learnings

Through this project I learned:

✅ Linux Server Administration
✅ AWS EC2 Deployment
✅ Git & GitHub Workflow
✅ Nginx Configuration
✅ Docker Containerization
✅ Docker Compose
✅ DevOps Project Lifecycle

