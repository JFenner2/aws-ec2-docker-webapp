# AWS EC2 + Docker Web App Project

## Overview
This project demonstrates how to deploy a simple web application using AWS EC2 and Docker. The goal was to simulate a real-world cloud deployment workflow using industry-standard tools.

---

## Architecture

GitHub → EC2 Instance → Docker → Nginx Container → Public Internet

---

## Technologies Used
- AWS EC2 (Ubuntu)
- Linux (command line administration)
- Docker (containerisation)
- Git & GitHub (version control)
- Nginx (web server)

---

## What I Built

- Launched an AWS EC2 instance
- Connected via SSH using key-based authentication
- Installed and configured Docker on a Linux server
- Built a custom Docker image using a Dockerfile
- Deployed a web server container
- Exposed the application to the internet via port 80
- Managed source code using Git and GitHub

---

## Key Learning Outcomes

- Understanding cloud compute (EC2)
- Linux server management basics
- Docker container lifecycle (build → run → expose)
- Networking fundamentals (ports and security groups)
- Git workflow (add → commit → push)

---

## How to Run This Project

1. Clone the repository:
   git clone <repo-url>

2. Build the Docker image:
   docker build -t my-first-app .

3. Run the container:
   docker run -d -p 80:80 my-first-app

4. Open in browser:
   http://<EC2_PUBLIC_IP>

---

## Status
Completed – Working deployment on AWS EC2# AWS EC2 Docker WebApp Project
