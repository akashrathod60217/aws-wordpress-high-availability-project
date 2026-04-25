# AWS Highly Available WordPress Deployment

![AWS](https://img.shields.io/badge/AWS-Cloud-orange)
![Project](https://img.shields.io/badge/Project-DevOps-blue)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)

---

## 📌 Project Overview
Designed and deployed a **highly available, scalable WordPress application** on AWS, simulating a real-world production environment using core cloud and DevOps practices.

---

## 🧰 Tech Stack
- **AWS Services:** EC2, RDS (MySQL Multi-AZ), S3, CloudFront, Application Load Balancer, Auto Scaling Group, IAM  
- **OS & Tools:** Linux, WordPress  

---

## 🏗️ Architecture Diagram
![AWS WordPress Architecture](https://raw.githubusercontent.com/akashrathod60217/aws-wordpress-high-availability-project/main/architecture.png)

---

## 🧠 Architecture Explanation
- User requests are routed through **CloudFront (CDN)** for low latency and caching  
- Traffic is forwarded to **Application Load Balancer (ALB)** for distribution  
- **Auto Scaling Group** dynamically manages multiple EC2 instances  
- **EC2 instances** host the WordPress application  
- **Amazon RDS (MySQL - Multi-AZ)** ensures high availability and reliability  
- **Amazon S3** stores static assets and backups  
- **IAM roles and Security Groups** enforce secure access control  

---

## 🚀 Key Features
- High Availability using **Multi-AZ architecture**  
- Automatic scaling with **Auto Scaling Group**  
- Efficient traffic distribution using **ALB**  
- Secure infrastructure with **IAM & Security Groups**  
- Improved performance using **CloudFront CDN**  

---

## ⚙️ Deployment Steps
1. Launched EC2 instances and installed WordPress  
2. Configured Application Load Balancer  
3. Set up Auto Scaling Group  
4. Created RDS MySQL database (Multi-AZ)  
5. Configured S3 bucket for storage and backups  
6. Set up CloudFront distribution  
7. Applied IAM roles and Security Groups  

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

## 🔐 Security Implementation
- Configured **IAM roles** for least-privilege access  
- Restricted database access using **Security Groups**  
- Controlled inbound and outbound traffic rules  

---

## 📈 Outcome
- Built a **production-like cloud architecture** with high availability  
- Achieved **fault tolerance** using Multi-AZ and Auto Scaling  
- Improved performance and latency using **CloudFront CDN**  
- Implemented secure and scalable infrastructure  

---

## ⚠️ Challenges Faced
- Connecting WordPress with RDS securely  
- Configuring correct Security Group rules  
- Managing ALB health checks and target groups  
- Ensuring proper Auto Scaling behavior  

---

## 🎯 Learnings
- Hands-on experience with AWS core services  
- Understanding of real-world cloud architecture  
- Designing scalable and fault-tolerant systems  

---

## 🚀 Future Improvements
- Implement CI/CD pipeline using GitHub Actions or Jenkins  
- Containerize application using Docker  
- Use Terraform for Infrastructure as Code  

---

## 🌐 Live Demo
(Add your CloudFront URL or ALB DNS here)

---
