# Containerization and Deployment of Portfolio Website using Docker and AWS EC2

## 📌 Project Overview

This project demonstrates the containerization and deployment of a static portfolio website using Docker and Amazon EC2. The website is packaged into a Docker container and deployed on a cloud-based virtual machine hosted on AWS.

The project also implements Continuous Integration and Continuous Deployment (CI/CD) using GitHub Actions, enabling automated deployment whenever changes are pushed to the GitHub repository.

---

## 🎯 Project Objectives

* Containerize a web application using Docker
* Create and manage Docker images and containers
* Deploy containerized applications on AWS EC2
* Configure a Linux-based cloud server
* Implement CI/CD using GitHub Actions
* Automate deployment using shell scripting
* Gain hands-on experience with DevOps practices

---

## 🛠 Technologies Used

* HTML5
* CSS3
* Docker
* Docker Hub
* AWS EC2
* Ubuntu Linux
* Git & GitHub
* GitHub Actions
* Nginx

---

## ✨ Features

* Containerized portfolio website
* Docker-based deployment
* AWS EC2 cloud hosting
* Automated deployment using GitHub Actions
* Shell script deployment automation
* Linux server management
* Version-controlled deployment workflow
* Continuous Integration and Continuous Deployment (CI/CD)

---

## 🏗 Architecture

Developer
│
▼
GitHub Repository
│
▼
GitHub Actions (CI/CD)
│
▼
AWS EC2 Instance
│
▼
Docker Container (Nginx)
│
▼
Portfolio Website

---

## ⚙️ Implementation Steps

### 1. Portfolio Website Preparation

* Developed a static portfolio website using HTML and CSS.
* Organized project files and assets.

### 2. Docker Containerization

* Created a Dockerfile for the application.
* Built Docker images locally.
* Tested application execution inside Docker containers.

### 3. AWS EC2 Setup

* Launched an Ubuntu EC2 instance.
* Configured security groups for HTTP access.
* Connected to the instance using SSH.

### 4. Docker Deployment on EC2

* Installed Docker on the EC2 instance.
* Cloned the GitHub repository.
* Built and deployed the Docker container.

### 5. Deployment Automation

* Created a deployment script (`deploy.sh`).
* Automated Docker build and container restart process.

### 6. CI/CD Integration

* Configured GitHub Actions workflow.
* Enabled automatic deployment on every push to the main branch.
* Verified successful end-to-end deployment.

---

## 📚 Learning Outcomes

Through this project, I gained practical experience in:

* Docker Images and Containers
* Dockerfile Creation
* AWS EC2 Deployment
* Linux Server Administration
* SSH Connectivity
* Git and GitHub Workflow
* Shell Script Automation
* CI/CD using GitHub Actions
* Cloud-based Application Deployment
* DevOps Fundamentals

---

## 📂 Project Structure

portfolio-website/
│
├── .github/
│   └── workflows/
│       └── deploy.yml
│
├── Dockerfile
├── deploy.sh
├── index.html
├── styles.css
├── assets/
│
└── README.md

---

## 🔗 Deployment

### GitHub Repository

https://github.com/Shejaldattatray/aws-portfolio

### Live Website

http://13.232.144.203

---

## 👨‍💻 Author

Shejal Jambhale

Cloud Computing & DevOps Intern

MIT Art, Design and Technology University

---

## ⭐ Future Enhancements

* HTTPS Configuration using SSL/TLS
* Custom Domain Integration
* Docker Compose for Multi-Container Applications
* Monitoring using Prometheus and Grafana
* Infrastructure as Code (Terraform)
* Container Orchestration using Kubernetes

