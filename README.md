# 🚀 CI/CD Pipeline using GitHub Actions & Docker

## 📌 Project Overview

This project demonstrates the implementation of a **CI/CD (Continuous Integration and Continuous Deployment)** pipeline using **GitHub Actions** and **Docker**.

The pipeline automates the process of building, testing, and deploying a simple Python-based web application, reducing manual effort and improving efficiency.

---

## 🛠️ Tools & Technologies Used

* **Python (Flask)** – Web application development
* **Docker** – Containerization
* **Docker Compose** – Multi-container management
* **GitHub Actions** – CI/CD automation
* **GitHub** – Version control
* **Docker Hub** – Image storage

---

## 📂 Project Structure

```
devops-cicd-project/
│
├── app.py
├── requirements.txt
├── Dockerfile
├── docker-compose.yml
└── .github/
    └── workflows/
        └── main.yml
```

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the Repository

```
git clone https://github.com/yourusername/devops-cicd-project.git
cd devops-cicd-project
```

### 2️⃣ Run the Application using Docker

```
docker-compose up --build
```

### 3️⃣ Access the Application

Open your browser and go to:

```
http://localhost:5000
```

---

## 🔄 CI/CD Pipeline Workflow

The pipeline is automatically triggered when code is pushed to the **main branch**.

### 🔹 Pipeline Steps:

1. Checkout source code from GitHub
2. Set up Python environment
3. Install dependencies
4. Run basic application test
5. Build Docker image
6. Push Docker image to Docker Hub

---

## 🔐 GitHub Secrets Configuration

Add the following secrets in your GitHub repository:

* `DOCKER_USERNAME`
* `DOCKER_PASSWORD`

---

## 🐳 Docker Configuration

Make sure to update the Docker image name in the workflow file:

```
yourusername/devops-app
```

Replace `yourusername` with your actual Docker Hub username.

---

## 📸 Output

* Flask application running locally
* Successful CI/CD pipeline execution
* Docker image available on Docker Hub

---

## 🎯 Key Features

* Automated build and deployment
* Containerized application
* Easy to scale and maintain
* Beginner-friendly DevOps implementation

---

## 📌 Conclusion

This project highlights how CI/CD pipelines can automate the software development lifecycle. By integrating GitHub Actions with Docker, deployments become faster, more reliable, and consistent across environments.

---
