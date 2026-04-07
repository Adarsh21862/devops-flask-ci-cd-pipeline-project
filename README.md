# 🚀 DevOps Project - Dockerized Application with CI/CD

## 📌 Overview

This project demonstrates a basic implementation of DevOps practices by building, containerizing, and automating a simple application. It showcases the integration of development and operations using modern tools and workflows.

DevOps is a set of practices that combines software development and IT operations to improve deployment speed and software quality. ([GitHub][1])

---

## 🎯 Objectives

* Understand DevOps fundamentals
* Learn version control using Git & GitHub
* Implement containerization using Docker
* Set up a basic CI/CD pipeline
* Automate application build and execution

---

## 🛠️ Tech Stack

* **Programming Language:** Python (Flask)
* **Version Control:** Git & GitHub
* **Containerization:** Docker
* **CI/CD Tool:** GitHub Actions
* **Operating System:** Linux (basic commands)

---

## 📂 Project Structure

```
Devops-1/
│── app.py
│── requirements.txt
│── Dockerfile
│── .github/
│    └── workflows/
│         └── ci.yml
```

---

## ⚙️ Features

* Simple Flask-based web application
* Docker containerization for easy deployment
* Automated CI pipeline using GitHub Actions
* Code versioning and collaboration via GitHub

---

## 🚀 Getting Started

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/Adarsh21862/Devops-1.git
cd Devops-1
```

---

### 2️⃣ Run Locally

```bash
pip install -r requirements.txt
python app.py
```

Open browser:
👉 http://localhost:5000

---

### 3️⃣ Run Using Docker

```bash
docker build -t devops-app .
docker run -p 5000:5000 devops-app
```

---

### 4️⃣ CI/CD Pipeline

* Automatically triggers on code push
* Installs dependencies
* Runs the application
* Ensures build success

---

## 📸 Output

When the application runs successfully, it displays:

```
Hello from DevOps Project 🚀
```

---

## 📚 Learning Outcomes

* Gained hands-on experience with DevOps workflow
* Learned Docker containerization
* Understood CI/CD pipeline basics
* Improved Git & GitHub usage

---

## 🔮 Future Improvements

* Deploy application on AWS EC2
* Add DockerHub integration
* Implement Kubernetes for scaling
* Add automated testing

---

## 👨‍💻 Author

**Adarsh Sarthak**

* BCA Student | DevOps Enthusiast
* GitHub: https://github.com/Adarsh21862

---

## ⭐ Acknowledgement

This project was built as part of my learning journey in DevOps and hands-on practice after completing a DevOps workshop.

---

## 📌 Note

This is a beginner-level project aimed at understanding core DevOps concepts and tools.

[1]: https://github.com/topics/devops?utm_source=chatgpt.com "devops · GitHub Topics · GitHub"
