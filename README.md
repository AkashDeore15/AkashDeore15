<div align="center">
  <img src="[https://capsule-render.vercel.app/api?type=waving&color=0:667eea,100:764ba2&height=200&section=header&text=Akash%20Deore&fontSize=60&fontColor=fff&animation=fadeIn&fontAlignY=35&desc=Cloud%20Security%20%26%20Platform%20Engineer&descAlignY=55&descSize=18](https://akashdeore.com/)" width="100%"/>
</div>

<div align="center">
  
  [![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/akash-deore)
  [![GitHub](https://img.shields.io/badge/GitHub-Follow-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Akashdeore15)
  [![Email](https://img.shields.io/badge/Email-Contact-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:akashdeore1999@gmail.com)
  [![Location](https://img.shields.io/badge/Location-Newark%2C%20NJ-00C851?style=for-the-badge&logo=google-maps&logoColor=white)](#)
  
  <br/>
  
  ![Profile Views](https://komarev.com/ghpvc/?username=AkashDeore15&color=667eea&style=for-the-badge&label=PROFILE+VIEWS)
  
</div>

---

## 🎯 Professional Summary

**Cloud Security Engineer** with **4+ years** of enterprise-grade experience delivering secure, scalable cloud infrastructure solutions across **AWS, Azure, and GCP**. Deep expertise in **Identity and Access Management (IAM)**, **Infrastructure as Code (IaC)**, and **security automation** aligned with **NIST frameworks** and **CIS Benchmarks**. Proven track record of reducing security incidents by **65%** through automated IAM governance pipelines and cutting infrastructure costs by **$16K+** while maintaining **99.9% data integrity**.

Completed my**Master of Science in Computer Science** at **New Jersey Institute of Technology** (Expected May 2026) while serving as a **Graduate Teaching Assistant** for networking courses. Former **Security Delivery Analyst** at **Accenture**, where I architected RBAC/ABAC frameworks, implemented SSO authentication flows, and built Python-based SIEM integrations that increased threat detection by **40%**.

**Core Competencies:** Cloud Security Architecture • IAM & Identity Governance • Infrastructure Automation • DevSecOps • Microservices Architecture • Compliance Engineering • Incident Response • Security Monitoring

---

## 🏗️ Cloud Security Architecture

```mermaid
graph TB
    subgraph "Frontend Layer"
        A[Web Application]
        B[Mobile Client]
    end
    
    subgraph "API Gateway & Security"
        C[API Gateway]
        D[WAF/DDoS Protection]
        E[Authentication Service]
    end
    
    subgraph "Identity & Access Management"
        F[Azure AD/Entra ID]
        G[SSO/SAML/OIDC]
        H[MFA Service]
        I[RBAC/ABAC Engine]
    end
    
    subgraph "Microservices Layer"
        J[User Service]
        K[Auth Service]
        L[Security Service]
        M[Compliance Service]
    end
    
    subgraph "Data & Storage"
        N[(PostgreSQL)]
        O[(Redis Cache)]
        P[S3/Blob Storage]
    end
    
    subgraph "Security & Monitoring"
        Q[SIEM Integration]
        R[Splunk/ELK Stack]
        S[Datadog Monitoring]
        T[Security Alerts]
    end
    
    subgraph "Infrastructure"
        U[Terraform/IaC]
        V[Docker/Kubernetes]
        W[CI/CD Pipeline]
    end
    
    A & B --> D
    D --> C
    C --> E
    E --> F
    F --> G & H & I
    C --> J & K & L & M
    J & K & L & M --> N & O
    L --> P
    J & K & L & M --> Q
    Q --> R & S
    R & S --> T
    U --> V
    W --> V
    V --> J & K & L & M
```

---

## 🔐 IAM Authentication Flow

```mermaid
sequenceDiagram
    participant User
    participant Client
    participant Gateway as API Gateway
    participant Auth as Auth Service
    participant AAD as Azure AD/Entra ID
    participant RBAC as RBAC Engine
    participant Service as Microservice
    participant SIEM as SIEM/Monitoring
    
    User->>Client: Login Request
    Client->>Gateway: POST /auth/login
    Gateway->>Auth: Validate Credentials
    Auth->>AAD: SAML/OIDC Request
    AAD->>Auth: Identity Token
    Auth->>RBAC: Check Permissions
    RBAC-->>Auth: Role Assignment
    Auth->>Auth: Generate JWT Token
    Auth-->>Gateway: JWT + Refresh Token
    Gateway-->>Client: Authentication Success
    Client->>Gateway: API Request + JWT
    Gateway->>Auth: Validate JWT
    Auth->>RBAC: Verify RBAC/ABAC
    RBAC-->>Auth: Authorization Granted
    Auth-->>Gateway: Token Valid
    Gateway->>Service: Forward Request
    Service-->>Gateway: Response
    Gateway-->>Client: Success
    Auth->>SIEM: Log Auth Event
    SIEM->>SIEM: Anomaly Detection
```

---

## 📊 Professional Journey

```mermaid
timeline
    title Career & Education Timeline
    section Education
        2017-2021 : Bachelor of Engineering
                  : Information Technology
                  : Savitribai Phule Pune University
        2024-2026 : Master of Science
                  : Computer Science
                  : New Jersey Institute of Technology
    section Professional Experience
        2021-2023 : Application Development Associate
                  : Accenture
                  : Azure AD & CI/CD
        2023-2024 : Security Delivery Analyst
                  : Accenture
                  : IAM & SIEM Integration
        2025-Present : Graduate Teaching Assistant
                     : NJIT Networking Courses
        2026-Present : Systems Administrator
                     : JM Technical Services Inc
```

---

## 💼 Professional Experience

### 🔹 Systems Administrator
**JM Technical Services Inc.** | *Jan 2026 - Present*

- 🚀 **Infrastructure Automation:** Provisioned scalable cloud infrastructure using **Infrastructure as Code (IaC)** principles with **Terraform** and **CloudFormation**, reducing deployment lead time by **20%** and enforcing security baselines for standardized account provisioning
- 🛡️ **Compliance Engineering:** Implemented automated compliance validation and security policy enforcement across multi-cloud environments, ensuring alignment with **NIST frameworks** and **CIS Benchmarks**
- 💾 **Disaster Recovery:** Engineered **Disaster Recovery (DR)** strategies for system migrations, ensuring **99.9% data integrity** and supporting business continuity for critical enterprise workflows
- 💰 **Cost Optimization:** Led technical evaluations and optimized cloud/on-premise resources, resulting in approximately **$16K reduction** in infrastructure costs while maintaining high availability

**Technologies:** Infrastructure as Code, Terraform, CloudFormation, NIST, CIS Benchmarks, Disaster Recovery

---

### 🔹 Security Delivery Analyst
**Accenture** | *Mar 2023 - Mar 2024*

- 🔐 **Identity Automation:** Automated secure access provisioning and identity governance pipelines using **Azure AD (Entra ID)** and **PowerShell**, eliminating manual bottlenecks and reducing identity-related incidents by **65%**
- 🎯 **Access Control Frameworks:** Implemented **RBAC/ABAC** access control frameworks and **SSO** authentication flows (**SAML/OIDC/OAuth 2.0**), improving compliance audit scores by **35%** and enforcing least privilege access across cloud environments
- 🔍 **Threat Detection:** Designed and deployed **Python-based APIs** integrated with **SIEM platforms** to detect IAM anomalies, increasing threat detection capabilities by **40%** and resolving security visibility gaps
- 🤝 **Cross-Functional Collaboration:** Collaborated with engineering stakeholders to align cloud security architectures with business objectives, achieving a **15% reduction** in operational costs

**Technologies:** Azure AD, Entra ID, PowerShell, RBAC, ABAC, SSO, SAML, OIDC, OAuth 2.0, Python, SIEM, IAM

---

### 🔹 Application Development Associate
**Accenture** | *Sep 2021 - Feb 2023*

- 👤 **Identity Lifecycle Management:** Managed **Azure AD (Entra ID)** and **Active Directory** identity lifecycles, including configuring **Conditional Access policies**, **MFA integration**, and automated compliance checks, maintaining **100% uptime** for identity workflows
- 🔄 **DevSecOps Pipelines:** Built **CI/CD pipelines** from scratch using **Azure DevOps** and **GitHub Actions**, integrating security controls for shift-left validation and enhancing deployment reliability by **45%**
- 🐳 **Container Orchestration:** Orchestrated containerized deployments using **Docker** and container orchestration tools, enhancing system reliability and decreasing release failures by **33%**

**Technologies:** Azure AD, Entra ID, Active Directory, MFA, CI/CD, Azure DevOps, GitHub Actions, Docker, Kubernetes

---

### 🔹 Graduate Teaching Assistant
**New Jersey Institute of Technology** | *Jan 2025 - Dec 2025*

- 📚 **Technical Instruction:** Facilitated technical troubleshooting for networking concepts including **TCP/IP**, **DNS**, and protocol analysis, delivering hands-on guidance to improve student comprehension
- 🎓 **Curriculum Support:** Assisted in course material development and provided mentorship for graduate-level computer science students

**Technologies:** TCP/IP, DNS, Network Protocol Analysis

---

## 🛠️ Technology Stack

### **Cloud Platforms & Infrastructure**
![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazon-aws&logoColor=white)
![Azure](https://img.shields.io/badge/Microsoft_Azure-0078D4?style=for-the-badge&logo=microsoft-azure&logoColor=white)
![GCP](https://img.shields.io/badge/Google_Cloud-4285F4?style=for-the-badge&logo=google-cloud&logoColor=white)
![EC2](https://img.shields.io/badge/Amazon_EC2-FF9900?style=for-the-badge&logo=amazon-ec2&logoColor=white)
![S3](https://img.shields.io/badge/Amazon_S3-569A31?style=for-the-badge&logo=amazon-s3&logoColor=white)

### **Security & Identity Management**
![Azure AD](https://img.shields.io/badge/Azure_AD-0078D4?style=for-the-badge&logo=microsoft-azure&logoColor=white)
![IAM](https://img.shields.io/badge/AWS_IAM-DD344C?style=for-the-badge&logo=amazon-aws&logoColor=white)
![OAuth](https://img.shields.io/badge/OAuth_2.0-3C873A?style=for-the-badge&logo=oauth&logoColor=white)
![SAML](https://img.shields.io/badge/SAML-FF6600?style=for-the-badge&logo=security&logoColor=white)

### **Infrastructure as Code & DevOps**
![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=for-the-badge&logo=terraform&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=github-actions&logoColor=white)
![Azure DevOps](https://img.shields.io/badge/Azure_DevOps-0078D7?style=for-the-badge&logo=azure-devops&logoColor=white)

### **Monitoring & Observability**
![Splunk](https://img.shields.io/badge/Splunk-000000?style=for-the-badge&logo=splunk&logoColor=white)
![ELK Stack](https://img.shields.io/badge/ELK_Stack-005571?style=for-the-badge&logo=elastic&logoColor=white)
![Datadog](https://img.shields.io/badge/Datadog-632CA6?style=for-the-badge&logo=datadog&logoColor=white)

### **Programming & Scripting**
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![PowerShell](https://img.shields.io/badge/PowerShell-5391FE?style=for-the-badge&logo=powershell&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=for-the-badge&logo=gnu-bash&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)

### **Databases & Storage**
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)

### **Frameworks & APIs**
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![REST API](https://img.shields.io/badge/REST_API-FF6C37?style=for-the-badge&logo=postman&logoColor=white)

---

## 🎯 Technical Expertise Breakdown

```mermaid
mindmap
  root((Akash Deore<br/>Cloud Security Engineer))
    Cloud Platforms
      AWS
        EC2
        S3
        SQS
        IAM
        CloudFormation
      Microsoft Azure
        Azure AD
        Entra ID
        Azure DevOps
      Google Cloud Platform
    Security & IAM
      Identity Governance
      RBAC/ABAC
      SSO Authentication
        SAML
        OIDC
        OAuth 2.0
      MFA Integration
      Conditional Access
      Threat Detection
    Infrastructure & DevOps
      Infrastructure as Code
        Terraform
        CloudFormation
      Containerization
        Docker
        Kubernetes
      CI/CD Pipelines
        GitHub Actions
        Azure DevOps
      Configuration Management
    Monitoring & Compliance
      SIEM Integration
      Splunk
      ELK Stack
      Datadog
      NIST Frameworks
      CIS Benchmarks
      Compliance Automation
    Programming
      Python
      Java
      PowerShell
      Bash
      JavaScript
      TypeScript
```

---

## 🚀 Featured Projects

### 🔐 Cloud Security User Management System

**Secure, Role-Based Authentication Platform with Automated CI/CD**

A production-grade user management system implementing enterprise security patterns with JWT-based authentication,
