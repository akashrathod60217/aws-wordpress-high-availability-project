# AWS Highly Available WordPress Deployment

![AWS](https://img.shields.io/badge/AWS-Cloud-orange)
![Project](https://img.shields.io/badge/Project-DevOps-blue)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)

## 📌 Project Overview
This project simulates a real-world production environment by deploying a highly available and scalable WordPress application on AWS.

---

## 🛠️ Services Used
- EC2 (Web Server)
- RDS (MySQL Database)
- S3 (Storage & Backup)
- CloudFront (CDN)
- Load Balancer
- Auto Scaling
- IAM (Security)

---

## 🏗️ Architecture Overview
- User requests are routed through CloudFront (CDN)
- Traffic is distributed using Application Load Balancer
- Auto Scaling ensures automatic scaling of EC2 instances based on traffic
- Multiple EC2 instances handle web requests
- RDS manages the MySQL database securely
- S3 is used for static content and backups
  
---

## 📸 Screenshots

### EC2 Setup
EC2 instances configured to host the WordPress application
![EC2](https://github.com/user-attachments/assets/c02a778c-e449-4991-94f4-ba71ecd3a127)

### RDS Database
Amazon RDS instance used for managing the MySQL database securely
![RDS](https://github.com/user-attachments/assets/a9dec9ed-0df0-42dc-82b2-b5461ef51780)


### S3 Bucket
S3 bucket configured to store static files and backups
![S3](https://github.com/user-attachments/assets/f6936f2d-f15e-4174-acd6-5e07d9a2ed24)

### CloudFront CDN
CloudFront distribution used to improve website performance and reduce latency
![cloudfront](https://github.com/user-attachments/assets/f337245f-0601-44e4-b691-36d94f8bd05c)


### Load Balancer
Application Load Balancer distributing incoming traffic across multiple EC2 instances
![loadbalancer](https://github.com/user-attachments/assets/3af3fdce-4219-4aab-8908-0c948603df84)

---
## 🚀 Key Features
- High Availability
- Auto Scaling
- Secure Infrastructure
- Fast Content Delivery

---
## 🔐 Security
- Configured IAM roles for secure access
- Restricted database access using security groups
- Enabled controlled inbound and outbound traffic

---

## AWS WordPress Architecture Image

- ![AWS WordPress Architecture](https://github.com/akashrathod60217/aws-wordpress-high-availability-project/blob/main/architecture.png)

---

## 📈 Outcome
Successfully deployed a scalable, secure, and highly available WordPress application using AWS services, simulating real-world production infrastructure.

---

## 🚀 Future Improvements
- Implement CI/CD pipeline using Jenkins or GitHub Actions
- Containerize application using Docker
- Use Terraform for Infrastructure as Code
 
---

## 🎯 Learnings
- Gained hands-on experience with AWS cloud services
- Understood real-world architecture design
- Learned how to build scalable and fault-tolerant systems
 
