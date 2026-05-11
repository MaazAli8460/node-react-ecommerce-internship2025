# MERN E-Commerce DevOps Deployment Project

## DevOps Internship Project

This repository contains the DevOps implementation and deployment work completed during my DevOps Internship.

The original MERN E-Commerce application was based on the tutorial project created by Basir. The application itself was forked and used as a practical environment for learning and implementing real-world DevOps workflows and deployment practices.

My primary contribution focused on:

* Docker containerization
* CI/CD automation
* Cloud deployment
* Linux server management
* Environment configuration
* Infrastructure setup
* Deployment workflows

---

# Project Overview

This project demonstrates how a full-stack MERN (MongoDB, Express.js, React.js, Node.js) application can be prepared for production-like deployment using modern DevOps practices.

The internship focused on bridging development and operations by automating deployment pipelines, containerizing services, and managing cloud infrastructure.

---

# Original Application Credits

The original MERN E-Commerce application was developed as part of:

## React & Node Tutorial - Full ECommerce in 5 Hours [2020]

Created by: Basir

Tutorial Link:
https://www.youtube.com/watch?v=Fy9SdZLBTOo

Original Repository:
https://github.com/basir/node-react-ecommerce

This repository was forked strictly for educational, internship, and DevOps deployment practice purposes.

---

# DevOps Contributions

## Docker Containerization

Implemented Docker-based containerization for application consistency and portability.

### Tasks Performed

* Created Docker configuration files
* Built Docker images
* Managed containerized application execution
* Configured container networking
* Improved deployment consistency across environments

### Technologies Used

* Docker
* Docker CLI

---

# CI/CD Pipeline Automation

Configured automated Continuous Integration and Continuous Deployment workflows.

### Tasks Performed

* Integrated GitHub Actions workflows
* Automated build processes
* Automated deployment pipelines
* Reduced manual deployment effort
* Improved release consistency

### CI/CD Features

* Automated workflow execution
* Build automation
* Deployment automation
* Repository integration
* Continuous Integration
* Continuous Delivery

### Technologies Used

* GitHub Actions
* GitHub Workflows
* Git
* GitHub

---

# Cloud Deployment

Deployed the application to cloud infrastructure and managed the runtime environment.

### Tasks Performed

* Configured Linux server environment
* Managed deployment setup
* Configured runtime dependencies
* Managed cloud hosting
* Connected application services

### Technologies Used

* AWS EC2
* Linux
* SSH
* Cloud Infrastructure

---

# Environment & Infrastructure Management

Handled deployment configuration and infrastructure setup.

### Tasks Performed

* Environment variable management
* Server configuration
* Runtime setup
* Infrastructure preparation
* Deployment optimization

---

# Application Features

## User Features

* Product Listing
* Product Details
* Shopping Cart
* Checkout Process
* User Authentication
* Order Placement

## Admin Features

* Product Management
* Order Management
* User Management

---

# Technology Stack

## Frontend

* React.js
* Redux
* Axios
* HTML5
* CSS3

## Backend

* Node.js
* Express.js
* MongoDB
* Mongoose
* JWT Authentication

## DevOps

* Docker
* GitHub Actions
* AWS EC2
* Linux
* CI/CD Pipelines

---

# Project Architecture

```bash
Client (React Frontend)
        │
        ▼
Backend API (Node.js + Express)
        │
        ▼
MongoDB Database
        │
        ▼
Docker Containers
        │
        ▼
CI/CD Pipeline (GitHub Actions)
        │
        ▼
AWS EC2 Deployment
```

---

# Repository Structure

```bash
node-react-ecommerce-internship2025/
│
├── frontend/                 # React Frontend
├── backend/                  # Node.js Backend
├── .github/workflows/        # GitHub Actions CI/CD Workflows
├── Dockerfile                # Docker Configuration
├── docker-compose.yml        # Multi-container Setup (if applicable)
├── README.md
└── package.json
```

---

# Getting Started

## Clone Repository

```bash
git clone https://github.com/MaazAli8460/node-react-ecommerce-internship2025.git
cd node-react-ecommerce-internship2025
```

---

# Local Development Setup

## Backend Setup

```bash
npm install
npm start
```

Backend runs on:

```bash
http://localhost:5000
```

---

## Frontend Setup

```bash
cd frontend
npm install
npm start
```

Frontend runs on:

```bash
http://localhost:3000
```

---

# Environment Variables

Create a `.env` file inside the backend directory:

```env
MONGO_URI=your_mongodb_connection
JWT_SECRET=your_secret_key
PORT=5000
```

---

# Docker Setup

## Build Docker Image

```bash
docker build -t ecommerce-app .
```

---

## Run Docker Container

```bash
docker run -p 3000:3000 ecommerce-app
```

---

# CI/CD Workflow

The project includes GitHub Actions workflows for:

* Automated Builds
* Continuous Integration
* Continuous Delivery
* Deployment Automation

---

# DevOps Concepts Practiced

During this internship project, I gained hands-on experience with:

* Docker Containerization
* CI/CD Pipeline Design
* GitHub Actions Automation
* Linux Server Administration
* AWS EC2 Deployment
* Environment Configuration
* Infrastructure Management
* Deployment Automation
* Production Deployment Workflows

---

# Learning Outcomes

This project helped strengthen my understanding of:

* Real-world DevOps workflows
* Cloud deployment lifecycle
* Infrastructure automation
* Application deployment pipelines
* Production-ready deployment practices
* Scalable deployment architecture

---

# Future Improvements

Potential future enhancements include:

* Kubernetes Deployment
* Terraform Infrastructure as Code
* Monitoring & Logging
* Nginx Reverse Proxy Setup
* SSL/HTTPS Configuration
* Automated Testing
* Load Balancing
* Multi-Environment Deployment

---

# Author

## Maaz Ali

Computer Science Student
DevOps Intern

GitHub: https://github.com/MaazAli8460

---

# License

This repository is intended for educational and internship demonstration purposes only.
