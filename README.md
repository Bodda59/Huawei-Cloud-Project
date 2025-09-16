# 🏗️ 3-Tier Cloud Architecture on Huawei Cloud  

This project was developed during my internship at **Huawei Cloud Department**.  
It demonstrates the design and deployment of a **secure, cost-optimized, and scalable 3-tier web application** using Huawei Cloud services.  

---

## 📌 Architecture Overview  

The project follows a **3-tier architecture**:  
- **Frontend:** React  
- **Backend:** Spring Boot  
- **Database:** PostgreSQL  

The entire solution was deployed on **Huawei Cloud** with multiple layers of security, scalability, and cost optimizations.  

---

## 🔐 Security Highlights  
- Restricted **SSH access** to ECS from my personal IP only.  
- Configured **security groups** so the PostgreSQL database communicates **only with ECS on a specific port**.  
- Protected the application with **Firewalls** and **Web Application Firewalls (WAF)**.  
- Routed ECS instances through a **single NAT Gateway** with an Elastic IP (EIP), minimizing exposure.  

---

## ⚙️ Deployment & Optimization  
- **Dockerized** the application (frontend + backend) for portability and consistency.  
- Added **startup scripts** to auto-run containers when ECS restarts.  
- Created **machine images** for quick scaling and provisioning.  
- Configured **Load Balancers (RLB & ELB)** to distribute traffic across WAFs and ECS instances.  
- Used **Auto Scaling Groups (ASG)** to ensure elasticity and high availability.  
- Adopted a **NAT-based design** to reduce costs and improve security (no need for public IPs on each ECS).  

---



## 📸 Architecture Diagram  
will be found in the documentation

---

## 🚀 Key Learnings  
- Balancing **security, scalability, and cost efficiency** in real-world cloud environments.  
- Hands-on experience with **Huawei Cloud services** (ECS, NAT Gateway, WAF, Load Balancers, Auto Scaling).  
- Integrating **modern application frameworks** (React, Spring Boot, PostgreSQL) into cloud infrastructure.  

---

## 🙏 Acknowledgments  
This project would not have been possible without the support and mentorship of my colleagues at **Huawei Cloud**.  

---

## 📖 Documentation  
For a detailed explanation of the architecture and deployment process, check out the [full project document](./docs/Project_Document.pdf).  

 
