# 🌐 Domain 5: Identity and Access Management (IAM) - CCSK Revision

## 🔑 Why IAM is Crucial in the Cloud
- **IAM** serves as the cloud’s **security perimeter**, replacing traditional network boundaries.
- It ensures **only authorized users** and entities can access sensitive resources.
- Misconfigurations here can lead to **serious security breaches**. Don’t underestimate the importance of getting IAM right!

## 🚀 Cloud-Specific IAM Challenges
- **🌍 Federation**: Managing identities across multiple cloud providers through **trust relationships** (standards-based protocols like OAuth, OpenID Connect).
- **🔄 Multiple IAM Systems**: Each cloud provider (AWS, Azure, GCP) has a unique IAM model—learn how to juggle them all.
- **🔓 Public Exposure**: Cloud admin interfaces are **internet-facing**, increasing the risk of unauthorized access.

## 📚 Key IAM Terms
- **Access Control**: Rules to **restrict access** to resources based on permissions.
- **Identity**: Attributes describing an entity in a specific context.
- **Authentication**: **Prove** who you are (e.g., password, token).
- **Authorization**: **Verify** what you're allowed to do (access to resources).
- **Multifactor Authentication (MFA)**: Add extra security (password + fingerprint, etc.).
- **Entitlements**: Map identities to authorizations (who gets access to what).

## 🤝 Federation & Identity Management
- **Federated Identity**: Centralized identity management across systems (IdP + RP).
- **Common Standards**: Use **OAuth** for authorization, **OpenID Connect** for authentication to allow secure access without sharing credentials.

## 🔒 Strong Authentication & Authorization
- **🔐 Authentication**:
  - **Multifactor Authentication (MFA)**: Use **multiple verification methods** to reduce account compromise risks (e.g., password + SMS, hard tokens).
  - **Passwordless Authentication**: Tokens or certificates replace passwords—good for convenience but not always for critical accounts.

- **📜 Authorization**:
  - **RBAC (Role-Based Access Control)**: Assign permissions based on predefined user roles.
  - **ABAC (Attribute-Based Access Control)**: Dynamic access decisions based on user **attributes** (time, location, role).
  - **PBAC (Policy-Based Access Control)**: Machine-readable policies determine access, allowing for conditions like **geolocation** or **time of day**.

## ⚙️ Privileged User Management
- **PIM (Privileged Identity Management)**: Manage **elevated access rights** (admin, superuser accounts) effectively.
- **PAM (Privileged Access Management)**: Control and audit **privileged access**, enforce **MFA**, and rotate credentials frequently to prevent misuse.

---

🎯 **Revise these key points before your exam!** Master IAM and you’ve locked down one of the cloud’s most critical components.
