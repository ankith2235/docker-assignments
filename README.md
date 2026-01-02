# Docker Assignment – 5 Projects

This repository contains Docker assignments completed as part of my Cloud & DevOps training. The projects demonstrate hands-on experience with Docker containers, images, Docker Hub, and Dockerfile automation using Ubuntu.

---

## 🔹 Project 1: Running Apache on Ubuntu Container
**Tasks Performed:**
1. Pulled Ubuntu container from Docker Hub  
2. Ran the container and mapped container port 80 to local port 80  
3. Installed Apache2 inside the container  
4. Verified Apache default page access via browser  

---

## 🔹 Project 2: Creating a Docker Image from Container
**Tasks Performed:**
1. Saved the container created in Project 1 as a Docker image  
2. Launched a new container from this image  
3. Mapped container port 80 to local port 81  
4. Started Apache2 service inside the container  
5. Verified access through browser  

---

## 🔹 Project 3: Docker Hub Image Upload and Deployment
**Tasks Performed:**
1. Used the Docker image created in Project 2  
2. Tagged and uploaded the image to Docker Hub  
3. Pulled the image on a separate machine  
4. Launched the container on port 80  
5. Started Apache2 service and verified browser access  

---

## 🔹 Project 4: Apache Automation Using Dockerfile
**Tasks Performed:**
1. Created a Dockerfile with the following specifications:
   - Ubuntu base image  
   - Apache2 installation  
   - Apache2 automatically starts when the container runs  
2. Built Docker image using the Dockerfile  

---

## 🔹 Project 5: Deploying Custom HTML Page Using Dockerfile
**Tasks Performed:**
1. Created a sample HTML file  
2. Used the Dockerfile from Project 4  
3. Replaced the default Apache web page with the custom HTML file inside the container  

---

## 🛠 Tools & Technologies Used
- Docker  
- Docker Hub  
- Amazon Web Services (AWS) – EC2 (Ubuntu AMI)  
- Linux  
- Git & GitHub  
- PuTTY (SSH access)

---

## 📌 Notes
- Detailed documentation and screenshots for each project are included in the assignment file available in this repository.
- These projects focus on real-world Docker usage and DevOps fundamentals.
