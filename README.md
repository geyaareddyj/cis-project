# ☁️ Cloud-Based Real-Time Chat and Messaging Application

A scalable, cloud-hosted messaging application designed to demonstrate the practical implementation of cloud infrastructure concepts through real-time communication.

## 📌 Project Overview

Large-scale messaging platforms provide reliable communication services, but their underlying cloud infrastructure and resource management mechanisms are not directly accessible for users to study, configure, or experiment with.

This project aims to develop a **Cloud-Based Real-Time Chat and Messaging Application** that provides a practical environment to explore how cloud infrastructure supports real-time communication.

The application will support individual and group messaging while demonstrating essential cloud computing concepts such as load balancing, auto-scaling, fault tolerance, cloud networking, and infrastructure monitoring.

## 🎯 Objectives

- Develop a real-time messaging application supporting individual and group conversations.
- Deploy and manage application servers using cloud infrastructure.
- Implement load balancing and auto-scaling to handle varying workloads.
- Explore fault tolerance and high availability through distributed server instances.
- Monitor infrastructure performance and resource utilization using cloud monitoring services.

## 🏗️ Proposed Cloud Architecture

The application will utilize Amazon Web Services (AWS) to deploy, manage, and monitor its infrastructure.

| AWS Service | Purpose |
|---|---|
| Amazon EC2 | Hosts the application backend. |
| EC2 Auto Scaling | Dynamically adjusts the number of server instances. |
| Amazon VPC | Provides an isolated cloud networking environment. |
| Public & Private Subnets | Organize internet-facing and internal resources. |
| Internet Gateway | Enables communication between the VPC and the internet. |
| NAT Gateway | Provides outbound internet access to private resources. |
| Route Tables | Control network traffic routing. |
| Application Load Balancer | Distributes incoming application traffic. |
| Security Groups | Control network access to AWS resources. |
| Amazon CloudWatch | Monitors infrastructure performance and resource utilization. |

## ✨ Key Features

- **Real-Time Messaging:** Instant message exchange between connected users.
- **Individual & Group Chats:** Supports private conversations and group communication.
- **Cloud Deployment:** Application hosted on AWS infrastructure.
- **Load Balancing:** Distributes incoming traffic across available servers.
- **Auto-Scaling:** Adjusts server capacity based on application workload.
- **Fault Tolerance:** Explores application availability during server failures.
- **Infrastructure Monitoring:** Tracks server health, performance, and resource utilization.

## 🛠️ Proposed Technology Stack

| Component | Technology |
|---|---|
| Frontend | React.js |
| Backend | Node.js, Express.js |
| Real-Time Communication | Socket.IO / WebSockets |
| Database | MongoDB Atlas |
| Cloud Platform | Amazon Web Services (AWS) |
| Authentication | JWT |
| Version Control | Git & GitHub |

## 👥 Project Team

**Team Members:**

1. Jalla Geya Reddy- 2520090123
2. Surapuraju Himasree- 2520090181
3. Salihundam Svara Haasni- 2520090170

**Project Guide:** Divya Priya Degala

## 📊 Expected Outcome

A functional cloud-based messaging application supported by an AWS infrastructure that demonstrates:

- Scalable application deployment.
- Efficient traffic distribution.
- Dynamic resource allocation.
- Infrastructure monitoring.
- Improved availability and fault tolerance.

The project aims to provide hands-on experience in designing, deploying, and evaluating cloud-based distributed applications.

## 📚 Domain

**Cloud Computing | Cloud Infrastructure | Distributed Systems**

---

*Developed as part of an academic Cloud Infrastructure project.*
