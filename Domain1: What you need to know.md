# Cloud Computing Study Guide

## 1. Understanding Cloud Computing

- **Definition**: Cloud computing is an on-demand model where you can access shared computing resources (e.g., networks, storage, applications) that are scalable and require minimal management effort.
- **NIST vs. ISO**: Both frameworks define cloud computing similarly, focusing on scalability, elasticity, and shared resource pools.

### Key Exam Points:
- Know the five essential characteristics:
  - Resource pooling
  - On-demand self-service
  - Broad network access
  - Rapid elasticity
  - Measured service
- Understand the three service models:
  - IaaS (Infrastructure as a Service)
  - PaaS (Platform as a Service)
  - SaaS (Software as a Service)
- Familiarize yourself with the four deployment models:
  - Public
  - Private
  - Hybrid
  - Community

---

## 2. Cloud Logical Model

Cloud computing abstracts resources and allows for their dynamic allocation, creating a multi-tenant environment where different users access shared resources without interference.


### Key Exam Points:
- Be ready to explain the difference between **virtualization** and **cloud computing**:
  - In virtualization, resources are separated.
  - Cloud adds orchestration to dynamically allocate resources on-demand.
    
![image](https://github.com/user-attachments/assets/ac78744a-3764-447f-a012-b9ea0e301055)

---

## 3. Cloud Service Models

- **IaaS (Infrastructure as a Service)**: You control the infrastructure (e.g., virtual machines, storage) but not the underlying hardware.
- **PaaS (Platform as a Service)**: Provides a platform to develop and deploy applications without managing the underlying hardware or infrastructure.
- **SaaS (Software as a Service)**: The provider handles everything, including application maintenance. The user just consumes the service.
![image](https://github.com/user-attachments/assets/e35ad294-d452-4aa7-ae2e-a136b2afe8a7)

### Key Exam Points:
- Understand the differences in control and responsibility in each model:
  - In SaaS, the provider controls more.
  - In IaaS, the user controls more.
- Know examples of each model:
  - **SaaS**: Gmail
  - **IaaS**: AWS

---

## 4. Cloud Deployment Models

- **Public Cloud**: Cloud infrastructure is owned and operated by a third-party provider and available to the public (e.g., AWS, Azure).
- **Private Cloud**: Infrastructure is operated solely for one organization.
- **Hybrid Cloud**: Combines private and public clouds, allowing for portability of data and applications.
- **Community Cloud**: Infrastructure is shared by several organizations with common concerns (e.g., security requirements).
![image](https://github.com/user-attachments/assets/e135c32e-c186-49e2-9703-367868ff13de)

### Key Exam Points:
- Be familiar with each model’s benefits and risks:
  - **Public Cloud**: Offers scalability but reduces control over security.

---

## 5. Security and Compliance in the Cloud

Cloud security is based on a **shared responsibility model**:
- **Provider**: Manages the security of the cloud (e.g., physical infrastructure).
- **User**: Responsible for security **in the cloud** (e.g., securing data, managing user access).
![image](https://github.com/user-attachments/assets/6236865e-a53e-4a11-86fc-604934c5668a)

### Key Exam Points:
- In SaaS, the provider handles most security.
- In IaaS, users are responsible for configuring their security.
- Understand compliance challenges in cloud:
  - Data privacy
  - Jurisdiction issues
  - Auditability
![image](https://github.com/user-attachments/assets/abe0bbdd-99b6-4004-aedf-edeebc74733d)
![image](https://github.com/user-attachments/assets/64fc864f-f59c-4264-8e27-9932c7f0a53d)

---

## 6. Exam Tips:
- Focus on understanding key cloud concepts like:
  - Elasticity
  - Multi-tenancy
  - Resource pooling
- Be familiar with the differences in responsibility between users and providers across service and deployment models.
- Pay attention to real-world scenarios where you'll need to assess security, compliance, and governance issues in a cloud environment.
