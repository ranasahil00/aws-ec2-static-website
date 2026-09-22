# AWS EC2 Static Website with Docker & GitHub Actions

A static website deployed on **AWS EC2** and containerized using **Docker**, with a **GitHub Actions CI pipeline** for automated Docker image builds.

---

## 📌 Project Overview

This project demonstrates the deployment of a static website on an AWS EC2 instance using Ubuntu and Nginx.

The project was later containerized using Docker to make the application portable and easy to deploy.

GitHub Actions is used to automatically build the Docker image whenever changes are pushed to the `main` branch.

---

## 🚀 Features

- Static website hosting
- AWS EC2 deployment
- Ubuntu Linux server
- Nginx web server
- Docker containerization
- Git and GitHub
- GitHub Actions CI
- Automated Docker image build

---

## 🛠️ Technologies Used

- AWS EC2
- Ubuntu
- Nginx
- Docker
- Git
- GitHub
- GitHub Actions
- HTML
- CSS

---

## 📂 Project Structure

```text
aws-ec2-static-website/
│
├── .github/
│   └── workflows/
│       └── deploy.yml
│
├── index.html
├── about.html
├── contact.html
├── projects.html
├── services.html
├── style.css
├── Dockerfile
└── README.md
