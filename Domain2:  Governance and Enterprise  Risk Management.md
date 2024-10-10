# CCSK Domain 2: Cloud Governance and Strategies – Study Content

## 1. Cloud Governance

### Key Concepts:
- **Cloud Governance Definition**: Ensures that cloud strategies align with business goals, manage risks, and comply with legal requirements.

### Governance Scope:
- **Shared Responsibility Model**: Security is shared between the Cloud Service Provider (CSP) and Cloud Service Customer (CSC).
- **Multi-Jurisdictional Challenges**: Cloud services span multiple regions with varying regulatory requirements (e.g., GDPR, CCPA).

### Focus Areas:
#### Cloud Adoption Drivers:
- **Cost Efficiency**: Moving from CapEx to OpEx reduces upfront infrastructure costs, but requires governance to avoid unchecked spending.
- **Speed to Market**: Rapid development and deployment is possible with cloud, but without governance, it can result in misconfigurations, security gaps, and inefficiencies.

#### Governance Risks:
- **Misconfigurations**: Without proper governance, issues like open S3 buckets can expose sensitive data.
- **Legal/Regulatory Complexities**: Regulations such as GDPR and CCPA apply differently depending on where data is stored and processed.
- **Shared Responsibility Risks**: Misunderstanding the shared responsibility model can leave gaps in security, such as patching systems in IaaS environments.

### Practice:
- Review how cloud governance impacts cloud service implementation and management.

---

## 2. The Governance Hierarchy

### Key Concepts:

#### Governance Frameworks:
- **Risk Frameworks**: E.g., NIST 800-30, ISO 27005 for cybersecurity risk management.
- **Program Frameworks**: E.g., NIST Cybersecurity Framework (CSF), ISO 27001.
- **Control Frameworks**: E.g., NIST 800-53, CSA Cloud Controls Matrix (CCM).

#### Governance Documents:
- **Policies**: Broad security requirements (e.g., access control).
- **Control Objectives**: Specific desired outcomes for risk minimization.
- **Technical Standards**: Detailed security measures (e.g., MFA enforcement).

### Focus Areas:

#### Governance Frameworks:
- **Risk Frameworks**: NIST 800-30, ISO 27005, and CIS RAM guide organizations in assessing and managing cybersecurity risks.
- **Program Frameworks**: NIST CSF and ISO 27001 define an organization's overall security program, aligning security with business objectives.
- **Control Frameworks**: Frameworks like NIST 800-53 and CSA CCM provide technical and procedural controls to ensure all necessary security measures are applied to cloud environments.

#### Governance Documents:
- **Policies**: Broad statements defining how security will be managed. For example, a Data Protection Policy may mandate encryption for sensitive data.
- **Control Objectives**: Focus on what security controls should achieve, such as ensuring customer data is encrypted using industry-standard methods.
- **Technical Standards/Guidance**: Define specific implementations for meeting control objectives, such as using AES-256 for encryption.

### Practice:
- Create governance policies and map them to specific control frameworks like ISO 27001.

---

## 3. Cloud Security Frameworks

### Key Concepts:
- **Cloud Controls Matrix (CCM)**: Security control objectives across 17 domains, aligned with standards like ISO 27001 and PCI DSS.
- **Security, Trust, Assurance, and Risk (STAR) Registry**: Provides transparency into CSP security practices via CAIQ submissions and certifications.

### Focus Areas:
#### Cloud Controls Matrix (CCM):
- **17 Control Domains**: Cover governance, risk management, and compliance, providing a comprehensive list of cloud-specific security control objectives.
- **Cross-mapping to Standards**: The CCM aligns with standards like ISO 27001, PCI DSS, and NIST 800-53, enabling streamlined compliance.

#### STAR Registry:
- **CAIQ (Consensus Assessments Initiative Questionnaire)**: CSPs use CAIQ to self-assess and disclose their security practices, based on the CCM.
- **CSA STAR Certification**: Independent third-party audits assess CSPs’ controls against the CCM. STAR certification demonstrates strong security controls.

### Practice:
- Review how CCM can map organizational security controls to cloud services.

---

## 4. Policies and Compliance

### Key Concepts:

#### Core Policies:
- **Information Security Policy**: Defines the organization’s general security posture and objectives.
- **Specific Policies**: Address specific areas such as data protection, acceptable use, and identity management.

#### Compliance Requirements:
- National regulations (e.g., GDPR, CCPA) and industry-specific standards (e.g., PCI DSS).

### Focus Areas:
#### Policy Enforcement:
- Security policies should align with internal business needs and external regulations. Key policies include:
  - **Data Protection Policy**: Ensures data is encrypted in transit and at rest.
  - **Access Control Policy**: Defines how access to cloud resources is restricted (e.g., least privilege principle).
  - **Incident Response Policy**: Defines how incidents are identified, reported, and remediated in cloud environments.

#### Compliance Monitoring:
- Ongoing monitoring ensures cloud services meet standards like GDPR, HIPAA, and PCI DSS.
  - **GDPR**: Requires personal data protection and breach reporting within 72 hours.
  - **PCI DSS**: Applies to payment data and mandates controls like encryption, access control, and logging.

### Practice:
- Write a data security policy and map it to GDPR requirements.

---

## Final Revision Checklist
✅ Understand cloud governance and shared responsibility models.  
✅ Know key cloud security frameworks (e.g., CSA CCM, NIST CSF).  
✅ Align governance with compliance requirements and frameworks (NIST 800-53, ISO 27001).  
✅ Create governance documents (policies, control objectives).  
✅ Familiarize yourself with the CSA STAR program for cloud service provider transparency.
