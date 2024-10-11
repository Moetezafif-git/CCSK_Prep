# CCSK Domain 5: Identity and Access Management (IAM)

## 1. How IAM Is Different in the Cloud
### Key Concepts:
- **IAM in Cloud vs. On-Premise**: In the cloud, IAM controls access to virtual resources that are distributed, multi-tenant, and scalable, unlike static, centralized on-premise environments.
- **Shared Responsibility Model**: IAM responsibilities are shared between the cloud service provider (CSP) and the customer (CSC). CSPs secure infrastructure, while CSCs manage identities and permissions.
- **Distributed and Elastic Systems**: Cloud systems are dynamic, with resources frequently spun up and down. IAM systems must adapt to this rapid change.

### Focus Areas:
- The dynamic nature of the cloud and the need for scalable IAM across rapidly changing infrastructure.
- Familiarize yourself with **Cloud IAM Tools**: AWS IAM, Azure AD, Google Cloud IAM.

### Practice:
- **Exercise**: Compare traditional on-premise IAM systems with cloud IAM implementations (e.g., user accounts, roles, and access policies).

---

## 2. Fundamental IAM Terms
### Key Concepts:
- **Identity**: An entity (e.g., user, system) interacting with cloud services, representing human users, applications, or services.
- **Authentication**: The process of verifying an identity. Examples include username/password, MFA, and biometric verification.
- **Authorization**: Defines what an authenticated user can do within a system (e.g., read, write, delete).
- **Principle of Least Privilege**: Users and systems should only have the minimum permissions necessary for their functions.
- **Roles**: Group permissions for easier management (e.g., Admin, Developer), applied to identities to enforce access controls.

### Focus Areas:
- Difference between **authentication** and **authorization**.
- **IAM Principles**: Understand least privilege and role-based access control (RBAC).
- **IAM Policies**: Define actions allowed or denied within a cloud environment.

### Practice:
- **Exercise**: Set up RBAC for a cloud application using IAM policies.

---

## 3. Federation
### Key Concepts:
- **Federated Identity**: Users from one domain (e.g., corporate directory) access resources in another domain (e.g., cloud provider) without separate credentials.
- **Single Sign-On (SSO)**: Users log in once to access multiple systems without repeated authentication.
- **Identity Providers (IdPs)**: Organizations like Okta, Azure AD authenticate users and assert their identity to cloud services.

### Focus Areas:
- **Federation Models**: Understand identity federation (linking identity across domains) vs. SSO (one set of credentials across services).
- **Common Standards**: Learn about SAML, OAuth, and OpenID Connect (OIDC).

### Practice:
- **Exercise**: Configure SSO for a cloud app using an identity provider like Okta or Azure AD with SAML or OAuth.

---

## 4. Strong Authentication and Authorization
### Key Concepts:
- **Multi-Factor Authentication (MFA)**: Requires more than one form of verification (e.g., something you know, something you have, something you are).
- **Conditional Access**: Applies security conditions based on user attributes, location, or device state before granting access.
- **Role-Based Access Control (RBAC)**: Assigns users roles with specific permissions.
  
### Focus Areas:
- **MFA Importance**: Understand why MFA is critical for securing cloud services.
- **RBAC vs. ABAC (Attribute-Based Access Control)**: ABAC uses flexible access conditions based on attributes, whereas RBAC is role-based.

### Practice:
- **Exercise**: Implement MFA for all privileged accounts in a cloud IAM system and set up RBAC for different organizational roles.

---

## Final Revision Checklist
✅ Understand how IAM in the cloud differs from traditional on-premise systems.  
✅ Learn core IAM concepts: identity, authentication, authorization, roles, policies.  
✅ Know how **Federated Identity** and **SSO** work. Familiarize yourself with standards like SAML and OAuth.  
✅ Implement MFA and conditional access for stronger authentication.  
✅ Review **RBAC** and **ABAC** to manage access controls effectively.  
