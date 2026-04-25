# AWS Highly Available WordPress Deployment

![AWS](https://img.shields.io/badge/AWS-Cloud-orange)
![Project](https://img.shields.io/badge/Project-DevOps-blue)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)

---

## 📌 Project Overview
This project demonstrates a highly available and scalable WordPress application deployed on AWS cloud infrastructure. It simulates a real-world production environment using core AWS services and best practices.

---

## 🛠️ Services Used
- EC2 (Web Server)
- RDS (MySQL Database - Multi-AZ)
- S3 (Storage & Backup)
- CloudFront (CDN)
- Application Load Balancer (ALB)
- Auto Scaling Group
- IAM (Security & Access Control)

---

## 🏗️ Architecture Diagram

![AWS WordPress Architecture](https://raw.githubusercontent.com/akashrathod60217/aws-wordpress-high-availability-project/main/architecture.png)

---

## 🧠 Architecture Explanation

- User requests are first routed through **CloudFront (CDN)** to reduce latency and improve performance  
- Traffic is forwarded to the **Application Load Balancer (ALB)** which distributes requests across multiple EC2 instances  
- **EC2 instances (Auto Scaling Group)** host the WordPress application and scale automatically based on demand  
- **Amazon RDS (MySQL - Multi-AZ)** provides a managed and highly available database backend  
- **Amazon S3** is used for storing static assets and backups  
- **IAM roles and Security Groups** ensure secure access and network control  

This architecture ensures **high availability, scalability, fault tolerance, and performance optimization**.

---

## 🚀 Key Features

- High Availability using Multi-AZ architecture  
- Auto Scaling to handle traffic spikes  
- Load Balancing for efficient traffic distribution  
- Secure access using IAM and Security Groups  
- Optimized content delivery using CloudFront CDN  

---

## ⚙️ Deployment Steps

1. Launch EC2 instances and install WordPress  
2. Configure Application Load Balancer  
3. Set up Auto Scaling Group  
4. Create RDS MySQL database (Multi-AZ)  
5. Configure S3 bucket for static storage  
6. Set up CloudFront distribution  
7. Configure IAM roles and Security Groups  

---

## 📸 Screenshots

### EC2 Setup
![EC2](https://github.com/user-attachments/assets/c02a778c-e449-4991-94f4-ba71ecd3a127)

### RDS Database
![RDS](https://github.com/user-attachments/assets/a9dec9ed-0df0-42dc-82b2-b5461ef51780)

### S3 Bucket
![S3](https://github.com/user-attachments/assets/f6936f2d-f15e-4174-acd6-5e07d9a2ed24)

### CloudFront CDN
![CloudFront](https://github.com/user-attachments/assets/f337245f-0601-44e4-b691-36d94f8bd05c)

### Load Balancer
![ALB](https://github.com/user-attachments/assets/3af3fdce-4219-4aab-8908-0c948603df84)

---

## 🔐 Security

- Implemented IAM roles for secure access  
- Restricted database access using Security Groups  
- Controlled inbound and outbound traffic  

---

## 📈 Outcome

Successfully deployed a scalable, secure, and highly available WordPress application using AWS services, simulating a real-world production environment.

---

## 🎯 Learnings

- Hands-on experience with AWS core services  
- Understanding of real-world cloud architecture  
- Learned to design scalable and fault-tolerant systems  

---

## 🚀 Future Improvements

- Implement CI/CD pipeline using Jenkins or GitHub Actions  
- Containerize application using Docker  
- Use Terraform for Infrastructure as Code  

---
