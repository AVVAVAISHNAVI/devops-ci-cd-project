# devops-ci-cd-project
Architecture Overview
This project implements a complete CI/CD pipeline for a containerized web application:
Source code is stored in GitHub.
On every push, GitHub Actions automatically builds the Docker image (CI).
The Dockerized application is deployed to an AWS EC2 instance (CD).
The application is accessible publicly through the EC2 public IP.

<img width="400" height="300" alt="image" src="https://github.com/user-attachments/assets/f46d8b67-bf91-4ec9-9b38-17d867cd8b88" />

Pipeline Flow: GitHub → GitHub Actions → Docker Container → AWS EC2 Deployment
