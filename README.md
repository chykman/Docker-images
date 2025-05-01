
---

# 🐳 Docker Images – Capstone Project

## 📘 Table of Contents
1. [Overview](#overview)  
2. [Working with Docker Images](#working-with-docker-images)  
3. [Docker Container Deployment](#docker-container-deployment)  
4. [Pushing to Docker Hub](#pushing-to-docker-hub)  

---

## 📌 Overview

This project demonstrates how to search, pull, build, run, and publish Docker images using real-world examples. It walks through container creation and pushing a custom image to Docker Hub.

---

## ⚙️ Working with Docker Images

### 🔍 Search Docker Images  
```bash
docker search ubuntu
```  
![Search Images](https://github.com/user-attachments/assets/5ccf4a96-ca03-4f25-879e-ec5ae036043e)

---

### ⬇️ Pull Ubuntu Image  
```bash
docker pull ubuntu
```  
![Pull Image](https://github.com/user-attachments/assets/82bdb3d4-4852-4697-a773-afc9bd858394)

---

### 📁 List Local Images  
```bash
docker images
```  
![List Images](https://github.com/user-attachments/assets/cc13477d-1fa9-464d-9e31-7c363227a826)

---

### 🌐 Install Nginx on the Server  
![Install Nginx](https://github.com/user-attachments/assets/f8bee1b3-14a4-476e-b6e5-6ab2a08610d5)

---

## 🏗️ Docker Container Deployment

### 📄 Create and Configure Dockerfile  
![Dockerfile](https://github.com/user-attachments/assets/45234c8b-eb40-4043-aa8a-fd6736e65d31)

---

### ✍️ Add HTML Content  
```bash
echo "Welcome to Darey.io" | sudo tee -a index.html
```  
![HTML File](https://github.com/user-attachments/assets/4c3a1906-664a-4313-bb14-5aa7ff7b2e1e)

---

### 🏗️ Build Docker Image  
```bash
docker build -t dockerfile .
```  
![Build Image](https://github.com/user-attachments/assets/00206d66-b0c9-4d28-8e88-faf91977abda)  
![Build Complete](https://github.com/user-attachments/assets/279025f2-1e0b-44f4-8678-d971c2f0bfb3)

---

### 🚀 Run Docker Container  
```bash
docker run -p 8080:80 dockerfile
```  
![Run Container](https://github.com/user-attachments/assets/515948db-bfd0-4d9d-8eb2-a5d29d72bc6b)

---

### 🔐 Add Security Group Rules  
![Security Group](https://github.com/user-attachments/assets/8496a484-772b-4012-a38d-e80d4f7c58ad)  
![Security Group](https://github.com/user-attachments/assets/256d7c00-e531-434b-9ded-a84eeec90f33)

---

### 📋 Check Containers  
```bash
docker ps -a
```  
![List Containers](https://github.com/user-attachments/assets/03106c66-d01d-4fc7-8c54-cfa2418f3f45)

---

### ▶️ Start Docker Container  
```bash
docker start [container_id]
```  
![Start Container](https://github.com/user-attachments/assets/484ca10a-4fd3-4764-ae60-ea8646539567)

---

### 🌐 Visit Public IP  
Open your browser and visit the EC2 public IP on port 8080.  
![Browser Result](https://github.com/user-attachments/assets/db4ad479-bf79-45b9-b9e4-11346d116576)

---

## ☁️ Pushing to Docker Hub

### 🛠️ Create Docker Hub Repository  
![Create Account](https://github.com/user-attachments/assets/c8120730-bff1-4778-a8ae-52f4a3cb1367)  
![Create Repo](https://github.com/user-attachments/assets/e65ba0c1-fd05-4241-9882-4a5e5f0e766a)  
![Repo Setup](https://github.com/user-attachments/assets/d81664b2-2170-48b5-9d3f-456bd6f8afb9)

---

### 🏷️ Tag Docker Image  
```bash
docker tag dockerfile chykman/dockerfile:latest
```  
![Tag Image](https://github.com/user-attachments/assets/9e0efec1-7c60-4cdd-a8e7-b12741d3cf33)

---

### 🔐 Login to Docker Hub  
```bash
docker login
```  
![Login](https://github.com/user-attachments/assets/560e6a5b-197a-45b0-b89d-84bd47d12f18)

---

### 📤 Push Image to Docker Hub  
```bash
docker push chykman/dockerfile:latest
```  
![Push Image](https://github.com/user-attachments/assets/488c0f26-6ec8-4e1e-aae2-c28d780be828)  
![New Repo](https://github.com/user-attachments/assets/4cd89b3d-5d50-4e5f-98be-edf711f99e9c)

---
