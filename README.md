# Serverless & Containerized Food Ordering Platform

## 🚀 Project Overview
This project is a **Cloud-Native Food Ordering Web Application** designed to solve the common problems of traditional web hosting, such as high operational costs and scalability bottlenecks. By utilizing a "Serverless First" methodology, the platform ensures high availability and operational efficiency without the need for manual server management.

## 👥 Group Members
* **Fatima Imran** (ID: BSSE23098)
* **Maleeka Musadiq** (ID: BSSE23106)
* **Binash Ahsan** (ID: BSSE23090)

## 🏗️ Key Features & Architecture
The system is built using a modern microservices architecture, ensuring that the frontend and backend can scale independently.

* **Containerization:** Both frontend and backend services are packaged using **Docker** for consistent behavior across all environments.
* **Serverless Deployment:** The application is orchestrated by **AWS ECS Fargate**, removing the need to manage EC2 instances.
* **Scalable Database:** Uses **Amazon DynamoDB** as a serverless key-value store for menu data and orders, ensuring single-digit millisecond latency.
* **Automated CI/CD:** A custom pipeline built with **PowerShell** and **AWS CLI** automates the build-and-deploy lifecycle to Amazon ECR.

## 📂 Project Structure
* `PROJECT PROPOSAL.pdf` - Project aim, objectives, and problem statement.
* `TECHNICAL REPORT.pdf` - Detailed technical documentation and system design.
* `Implementation_steps_SS.pdf` - Step-by-step screenshots of the deployment process.
* `Project_Demo.mp4` - A video walkthrough of the working platform.
* `Prompt_logs.pdf` - Records of AI assistance and development logs.
* `Poster_Food_ordering_platform.pdf` - Visual summary of the project.

---
*Developed as part of the SCD Semester Project.*
