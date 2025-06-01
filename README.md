# 🔐 AWS Security & DevSecOps Projects by Domain

Welcome! This repository showcases a collection of hands-on **AWS Security** and **DevSecOps** projects, organized by security domains and automation pipelines.

My goal is to demonstrate how real-world AWS services, security controls, and DevSecOps practices can be applied to:
- Design secure and scalable cloud architectures  
- Automate threat detection and remediation  
- Enforce IAM best practices and compliance  
- Build secure CI/CD pipelines and monitor infrastructure in real time  

Whether you're a Cloud Security Engineer, GRC Analyst, or DevSecOps practitioner, you'll find practical implementations mapped to industry best practices and tools.

---
---

### 🧭 Project Overview

| Domain | Focus Area | Sample Topics |
|--------|------------|---------------|
| Threat Detection & Incident Response | Real-time alerting and auto-remediation | IAM credential revocation, public S3 auto-remediation |
| Security Logging & Monitoring | Centralized visibility and observability | CloudWatch, Lambda log triggers |
| Infrastructure Security | Network-level protection and segmentation | VPC design, VPN, endpoints, private S3 |
| Identity & Access Management (IAM) | Federated access and least privilege | SSO, Web Identity Federation, cross-account access |
| Data Protection | Encryption and secure storage | S3 object encryption |
| Management & Governance | Compliance, architecture & assessments | Terraform IaC, Prowler scanning, secure baselines |

---


## AWS Security

#### ⚡ Domain 1: **Threat Detection & Incident Response**

- evoke IAM Role Temporary Security Credentials 
- Auto-Remediate Public S3 Buckets

---

#### 👮 Domain 2: **Security Logging and Monitoring**

- S3 Events Triggering Lambda for Alerts
- Metrics Collection with CloudWatch Agent

---

#### 🔐 Domain 3: **Infrastructure Security** 

- Custom VPC Segmentation with Security Groups and NACLs 
  → [4-Tier Secure Network Architecture (AWS)](https://github.com/KwesiLovesTech/Four-Tier-Secure-Network-Architecture-AWS-.git)

- Site-to-Site VPN Setup
- VPC Endpoints for Private Service Access
- Private S3 Bucket Configuration

---

#### 🔑 Domain 4: **Identity & Access Management (IAM)**

- Web Identity Federation Implementation
- Single Sign-On (SSO) Integration
- Cross-Account Access to S3 with IAM Roles

---

#### 💾 Domain 5: **Data Protection**

- S3 Object Encryption (SSE-S3, SSE-KMS)

---

#### 🏫 Domain 6: **Management and Security Governance**

- AWS Secure Architecture Design with Terraform
  → [Base Networking Infrastructure for 3-Tier Architecture]()

- Prowler Security Assessment & Remediation

---

##### 🛠️ Tools & Technologies

- **AWS Services**: IAM, S3, VPC, Lambda, CloudWatch, Systems Manager, GuardDuty, Prowler
- **Infrastructure as Code**: Terraform
- **Security Concepts**: Least privilege, segmentation, logging, incident response, encryption
- **Languages**: Bash, HCL, Python (Lambda)

---

##### 📌 Purpose

This repository serves as a reference for:
- Cloud Security Engineers
- GRC and Compliance Analysts
- Learners and homelabbers exploring AWS security best practices

----

## Devops  &  DevSecOps

#### 🔧  [**CI/CD Pipeline with Jenkins & Ansible**](https://github.com/KwesiLovesTech/jenkins-cicd-pipeline.git)
- Fully automated Jenkins pipeline for a Java web app  
- Stages: Build → Test → Quality Gate → Artifact Push → Deploy  
- Tools: Jenkins, Nexus, SonarQube, EC2, GitHub


#### 🛠️  [**Terraform Infrastructure with Embedded Security**]()
- Deploy VPC, EC2, RDS with security controls baked in  
- Enforce encryption, logging, backups via Terraform modules  
- Tags and IAM policies integrated for audit readiness

#### 📦 [**CI/CD for Static Website on S3 using AWS CodePipeline**](https://github.com/KwesiLovesTech/kwesilovestech.com-static-website-deploy.git)
- **Frontend**: Static website hosted on Amazon S3 with CloudFront (optional)
- **CI/CD**: AWS CodePipeline + CodeBuild + GitHub for deployment automation
- [**Visitor Counter Backend**](https://github.com/KwesiLovesTech/kwesilovestech.com-static-website-deploy.git):
  - **API Gateway** (REST)
  - **Lambda** (Lambda function)
  - **DynamoDB** (stores and updates visit counts)

#### [🚧 **DevSecOps Pipeline: Secure Software Supply Chain**]()
- Jenkins pipeline with:
  - ✅ SonarQube (SAST)
  - ✅ Trivy (container scanning)
  - ✅ Gitleaks (secret scanning)
- Stops the build on policy violations


#### [**Monitoring & Alerting with Prometheus + Grafana**](https://github.com/KwesiLovesTech/jenkins-cicd-pipeline.git)
- Real-time monitoring for EC2 and containers  
- Alerting rules for CPU, memory, disk usage  
- Infrastructure deployed using Ansible


<br>

![AWS](https://img.shields.io/badge/AWS-Security-orange?logo=amazonaws)
![Terraform](https://img.shields.io/badge/IaC-Terraform-844FBA?logo=terraform)
![CI/CD](https://img.shields.io/badge/DevSecOps-Enabled-blueviolet?logo=githubactions)
![License: MIT](https://img.shields.io/badge/license-MIT-brightgreen.svg)


