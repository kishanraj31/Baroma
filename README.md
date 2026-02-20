# 🚀 Baroma – Production Deployment using Cloud & DevOps Practices

This project demonstrates how a web application is delivered to production using real DevOps workflow principles instead of just running locally.

The frontend (HTML/CSS) acts as the application artifact, while the main objective of this project is **deployment, hosting, version control and production delivery lifecycle**.

---

## 🎯 Project Objective

To simulate how applications are actually shipped in industry:

Local Development → Version Control → Remote Server → Web Server → Public Access

This is not a static website project.
This is a **production deployment implementation** using a frontend app as the deployable unit.

---

## 🧱 System Architecture

Developer Machine
⬇
Git Repository (Source Control)
⬇
SSH Remote Server (Linux VM)
⬇
Nginx Web Server
⬇
Public Internet Access

The application is hosted on a cloud virtual machine and served as a production service.

---

## ⚙️ DevOps Workflow Implemented

1. Developed application locally
2. Managed versions using Git
3. Pushed code to GitHub repository
4. Connected to remote Linux server using SSH
5. Installed and configured Nginx
6. Moved build files into server web root directory
7. Hosted application over public IP
8. Verified live production access from mobile & external network

This simulates a manual CI/CD delivery pipeline.

---

## ☁️ Cloud & Infrastructure

* Linux Virtual Machine (Remote Server)
* Public IP Hosting
* SSH Secure Access
* Nginx Reverse Serving
* Production directory deployment
* Internet-accessible service

---

## 🔁 CI/CD Concept Demonstrated

Every code update follows deployment lifecycle:

Code Change → Commit → Push → SSH → Update Server → Refresh Production

This models how application releases work before automation pipelines are introduced.

---

## 🛠️ Technologies Used

### Application Layer

* HTML5
* CSS3
* Responsive Layout (artifact only)

### DevOps & Infrastructure

* Linux
* SSH
* Git & GitHub
* Nginx
* Remote Hosting
* Production Deployment

---

## 📡 Live Service

Application is served via public server IP and accessible across devices (desktop & mobile), validating real hosting instead of localhost testing.

---

## 📌 Learning Outcome

This project focuses on understanding **how software reaches users**, not just how UI is built.

Key concepts practiced:

* Deployment lifecycle
* Remote infrastructure interaction
* Hosting configuration
* Release workflow
* Production verification

---

## 🧠 Key Takeaway

Frontend code is temporary — deployment pipeline is permanent.

The goal of this project was to practice delivering software, not just writing it.
