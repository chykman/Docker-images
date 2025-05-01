
---

# Docker Images – Capstone Project

##  Table of Contents  
1. [Project Overview](#project-overview)  
2. [Project Objectives](#project-objectives)  
3. [Project Deliverables](#project-deliverables)  
4. [Step-by-Step Implementation](#step-by-step-implementation)  
5. [Result and Validation](#result-and-validation)

---

##  Project Overview  
This capstone project demonstrates how to **create custom Docker images**, push them to **Docker Hub**, and run containers based on those images. It aims to familiarize users with containerization and image publishing using Docker.

---

##  Project Objectives  
- Create a working Dockerfile for a static web server.  
- Build and verify a Docker image locally.  
- Publish the Docker image to Docker Hub.  
- Pull and run the image from Docker Hub on another system.  

---

##  Project Deliverables  
✔ A Dockerfile for a custom web container  
✔ Built image hosted on Docker Hub  
✔ Verified local and remote container deployment  
✔ Screenshots of each command and result

---

##  Step-by-Step Implementation

### 1. Start a New EC2 Instance  
Log in to your EC2 instance to begin the Docker image creation process.  
![image](https://github.com/user-attachments/assets/e23f6b48-9018-4e8b-87a7-620a10aa4e61)

---

### 2. Create a Project Directory  
Make a new directory for your Docker project.  
![image](https://github.com/user-attachments/assets/331bb9b7-9e07-4f58-b879-7ea61bc88b1e)

---

### 3. Create `index.html`  
Write a simple HTML page that will be served from the Docker container.  
![image](https://github.com/user-attachments/assets/4c23f77e-60a3-442f-8f5c-e92e6d04b759)

---

### 4. Create a `Dockerfile`  
Define how the image is built and what it runs.  
![image](https://github.com/user-attachments/assets/3615797e-2017-4f56-a1b3-0f02a5252bfb)

---

### 5. Build the Docker Image  
Run `docker build` to generate the image locally.  
![image](https://github.com/user-attachments/assets/73c17f5f-4372-4450-8ab3-e1cc790cfa15)

---

### 6. List Docker Images  
Verify that the image was created successfully.  
![image](https://github.com/user-attachments/assets/f5f92c97-1579-4408-a7eb-5e3441dba448)

---

### 7. Run Docker Image  
Use the `docker run` command to launch the container from your new image.  
![image](https://github.com/user-attachments/assets/e13a37dc-d89c-4c3b-ade4-fc7e885b6d8f)

---

### 8. Docker Hub Login  
Log in to Docker Hub from the terminal.  
![image](https://github.com/user-attachments/assets/9a57e36e-d0ce-4175-869e-5e7a9847e927)

---

### 9. Tag and Push Image to Docker Hub  
Tag your image appropriately and push it to your Docker Hub repository.  
![image](https://github.com/user-attachments/assets/0ea4185a-2c2c-4a1b-8205-180df4716f7c)

---

### 10. Verify Push  
Visit Docker Hub to confirm the image was uploaded.  
![image](https://github.com/user-attachments/assets/cb1fa177-cdf2-47dc-871b-e0e50cd33128)

---

##  Result and Validation  
You have successfully created a Docker image, uploaded it to Docker Hub, and verified its deployment. This demonstrates a working knowledge of container creation, image building, and publishing to a cloud-based registry.

---
