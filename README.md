# 🚀 Flask Docker ECS AWS Deployment Project

## 📌 Project Overview
This project demonstrates a complete cloud deployment of a Flask web application using Docker and AWS services. The application is containerized and deployed using Amazon ECR, ECS Fargate, and exposed to the internet using an Application Load Balancer (ALB).

---

## 🏗️ Architecture Flow
Flask App → Docker Image → Amazon ECR → ECS Fargate → Application Load Balancer → Public Access

---

## ⚙️ Tech Stack
- Python (Flask)
- Docker
- AWS ECR (Elastic Container Registry)
- AWS ECS Fargate (Serverless Containers)
- AWS ALB (Application Load Balancer)

---

## 📁 Project Files
- app.py (Flask application)
- requirements.txt (Dependencies)
- Dockerfile (Container setup)

---

## 🚀 Deployment Steps
1. Created Flask application
2. Dockerized the application
3. Built Docker image locally
4. Pushed image to Amazon ECR
5. Created ECS Cluster (Fargate)
6. Defined Task Definition and Service
7. Configured Application Load Balancer
8. Accessed application via ALB DNS

---

## 🌐 Live Application
The application is successfully deployed and accessible via AWS Application Load Balancer.

👉 Output:
Hello from Flask Docker App 🚀

---

## 📸 Screenshots

### Flask App Working (ALB Output)
<img width="1920" height="1020" alt="image" src="https://github.com/user-attachments/assets/ffefa15d-acdc-4015-9a86-211aa87126b6" />

### ECR Repository
<img width="1920" height="1020" alt="image" src="https://github.com/user-attachments/assets/6f84e92c-01b4-418e-a9c0-42cebe19ca0b" />

### ECS Cluster & Task Running
<img width="1920" height="1020" alt="image" src="https://github.com/user-attachments/assets/78786fac-3d82-4488-b9ae-ba71db0bae0d" />

### Target Group Health
<img width="1920" height="1020" alt="image" src="https://github.com/user-attachments/assets/24718766-0107-40c4-8857-8b5bd157880f" />

### Application Load Balancer
<img width="1920" height="1020" alt="image" src="https://github.com/user-attachments/assets/abcfad4f-873e-4213-b602-8699ff2d0a16" />

---

## 🎯 Key Learnings
- Docker containerization of Flask apps
- AWS ECR image storage and management
- ECS Fargate serverless deployment
- Load balancing using ALB
- End-to-end cloud deployment pipeline

---

## 👩‍💻 Author
Sayali Fursule  
BE IT Graduate | Cloud & DevOps Enthusiast




