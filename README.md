# AWS EC2 Static Website with Docker & GitHub Actions

A static website deployed on **AWS EC2** and containerized using **Docker** with an automated **GitHub Actions CI pipeline**.

This project demonstrates the practical use of AWS EC2, Linux, Nginx, Docker, Git, GitHub, and GitHub Actions to build and manage a simple cloud-based web deployment.

---

## 📌 Project Overview

The project started as a static website hosted on an AWS EC2 instance running Ubuntu.

The website was then containerized using Docker and served through Nginx.

GitHub Actions was added to automate the Docker image build whenever new code is pushed to the `main` branch.

### Current Workflow

```text
Developer
    |
    v
GitHub Repository
    |
    v
GitHub Actions
    |
    v
Docker Build
    |
    v
Docker Image
