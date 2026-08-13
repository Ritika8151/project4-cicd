# Jenkins + Docker CI/CD Pipeline

## Project Overview

This project demonstrates a basic CI/CD pipeline using Jenkins and Docker.

The application is automatically built, containerized, and deployed using a Jenkins pipeline.

## Technologies Used

- Jenkins
- Docker
- GitHub
- Nginx
- Linux / Ubuntu
- AWS EC2

## CI/CD Pipeline

GitHub
   ↓
Jenkins
   ↓
Docker Build
   ↓
Docker Container
   ↓
Nginx Web Application

## Jenkins Pipeline Stages

1. Checkout source code from GitHub
2. Build Docker image
3. Remove previous container
4. Run new Docker container
5. Verify application

## Docker

The application is packaged using a Dockerfile based on Nginx.

## Deployment

The application runs inside a Docker container on an AWS EC2 instance.

## Learning Outcomes

- Jenkins pipeline creation
- Docker image creation
- Docker container deployment
- CI/CD automation
- GitHub integration
- Linux server deployment
