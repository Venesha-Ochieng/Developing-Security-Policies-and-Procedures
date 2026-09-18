# INTERNATIONAL CYBERSECURITY AND DIGITAL FORENSICS ACADEMY

## GRC102: INFORMATION SECURITY GOVERNANCE

### Week 2 Practical Laboratory: Developing Security Policies and Procedures

| Field | Details |
|---------|---------|
| Full Name | Venesha Adhiambo Ochieng |
| Registration Number | C11/26/CGRCE/17566 |
| Email Address | c11.cgrce2617566@icdfa.edu.ng |
| Cohort / Batch | Cohort11 |
| Date Submitted | 18th September 2026 |

---

# 1. Laboratory Scenario

NexusTech Solutions, a rapidly growing mid-sized software development company specializing in cloud-based enterprise resource planning (ERP) systems. The organization has expanded from 50 to 250 employees and has recently acquired high-profile clients in the financial and healthcare sectors.

You have been appointed Information Security Manager and have discovered that the company still relies on a five-year-old “IT Rules” document that mixes high-level policy intent, technical configuration instructions and vague recommendations. This has created inconsistent practices, unclear accountability and compliance gaps.

CEO Marcus Vance has directed you to establish a formal, structured and maintainable information security policy framework. Your mission is to build the foundation using the Security Policy Development Lifecycle so that NexusTech can strengthen governance, support ISO/IEC 27001 and SOC 2 readiness, and protect its growing information assets.

# Task 1 Establish the Security Policy Hierarchy

The IT Director, Sarah Jenkins, is confused about the difference between a policy and a procedure. A recent document titled “Password Policy” contains step-by-step Active Directory reset instructions, illustrating the documentation problem you must correct.

## Required Evidence Task 1

### 1.1 Hierarchy Definition Table defining Policy, Standard, Guideline and Procedure, including purpose, authority, mandatory/recommended nature and level of detail.

| Document Type | Definition | Purpose | Authority | Mandatory/ Recommended | Level of Detail |
|---------------|------------|---------|-----------|------------------------|----------------|
| Policy | High-level document that defines the organization's position, requirements, and management intent. Answers "what" needs to be done and "why" it matters. | Establishes what NexusTech requires and why, setting direction for the risk area. | Approved by senior leadership / the CEO or an appropriate governance authority | Mandatory | High-level. States principles and requirements only. No technical steps. |
| Standard | A document specifying mandatory, measurable requirements that support a policy. | Mandatory requirement that supports a policy by providing specific details on what must be implemented. Defines minimum requirements and acceptable behaviours. | Issued under the authority of an approved policy; approved and maintained by IT/Security leadership or the responsible function under delegated authority. | Mandatory | Mid-level. Concrete and specific (numbers, settings, thresholds), but not step-by-step. |
| Procedure | A document containing step-by-step instructions for how a specific activity should be performed. | Recommended approach that is not mandatory but provides best practices and suggested methods for implementing policies and standards. | Owned, developed, and maintained by the operational function/department manager responsible for the activity. | Mandatory when required by the governing policy/standard | Very detailed. Sequential, action-oriented, often system- or tool-specific. |
| Guideline | A document offering recommended approaches and good practice for implementing policies and standards. | Step-by-step instructions that detail exactly "how" to implement policies, standards, and guidelines. Provides operational guidance for specific tasks. | Developed by relevant subject-matter experts or issued by IT/Security as advisory guidance. | Recommended | Advisory. Explains options and reasoning rather than commanding one fixed action. |

### 1.2 Categorisation table for all eight statements, with a one-sentence justification for each classification.

| # | NexusTech Statement | Classification | Justification |
|---|---------------------|----------------|--------------|
| 1 | All NexusTech employees must use multi-factor authentication (MFA) when accessing the corporate network remotely. | Policy | States a mandatory, organization-wide requirement the "what" and "why" with no technical implementation detail. |
| 2 | To configure MFA on your mobile device, download the Authenticator app, scan the QR code provided in the IT portal, and enter the six-digit verification code. | Procedure | Gives sequential, action-oriented, step-by-step instructions a user follows in order to complete a specific task. |
| 3 | It is recommended that developers use parameterised queries to reduce SQL injection risk. | Guideline | The advisory language ("it is recommended") signals good practice rather than a compulsory rule, giving developers a suggested and not mandated method. |
| 4 | NexusTech is committed to protecting the confidentiality, integrity and availability of all client data. | Policy | A high-level statement of management intent and organizational commitment, setting overall direction rather than a specific rule. |
| 5 | All corporate laptops must have full-disk encryption enabled using BitLocker (Windows) or FileVault (macOS). | Standard | A specific, measurable, mandatory technical baseline naming the approved tools that operationalizes a broader data-protection policy. |
| 6 | Employees should avoid connecting to public, unsecured Wi-Fi networks when travelling. | Guideline | The word "should" signals recommended behaviour, offering advice rather than imposing an absolute, mandatory requirement. |
| 7 | In the event of a suspected security breach, employees must immediately contact the IT Helpdesk at extension 5555. | Procedure | A specific, actionable step within an incident- tells employees exactly what to do and how, when a defined event occurs. |
| 8 | Passwords must be a minimum of 14 characters and contain at least one uppercase letter, one lowercase letter, one number and one special character. | Standard | A precise, mandatory, measurable configuration requirement that can be consistently implemented and tested. |

### 1.3 A simple hierarchy diagram showing how policy flows into standards, procedures and guidelines.

```text
                        POLICY
                           │
                           │
            Defines management intent,
            objectives and requirements
                           │
          ┌────────────────┼────────────────┐
          │                │                │
          ▼                ▼                ▼
      STANDARD        PROCEDURE       GUIDELINE
          │                │                │
  Defines mandatory   Defines step-   Provides recommended
  technical and       by-step          best practices and
  operational         instructions     implementation advice
  requirements        for execution    and flexibility
          │                │                │
          └────────────────┴────────────────┘
                           │
                           ▼
                     IMPLEMENTATION
                     & COMPLIANCE
```

# Task 2 Draft an Effective Acceptable Use Policy

NexusTech currently has no formal rules governing company-provided devices or acceptable behaviour on the corporate network. Unauthorised software downloads and extensive personal use have increased malware and compliance risk.

Draft a complete Acceptable Use Policy (AUP).

## 2.1 Policy Title and Version Control

| Document Information | Details |
|---------------------|---------|
| Policy Title | Acceptable Use Policy (AUP) |
| Version | 1.0 |
| Policy Owner | Information Security Manager |
| Approval Authority | Marcus Vance, Chief Executive Officer |
| Effective Date | 18th September 2026 |
| Review Date | 18th September 2027 |

## 2.2 Purpose

This Policy establishes clear requirements for the appropriate, secure and responsible use of NexusTech Solutions' information systems, networks, company-provided devices, applications, cloud services and other technology resources.

The Policy is intended to protect the confidentiality, integrity and availability of NexusTech and client information including the financial and healthcare sector client data that NexusTech now processes, reduce malware and unauthorized-access risk, support business operations and enable employees to work productively while using organizational technology resources responsibly.

## 2.3 Scope

This Policy applies to all NexusTech employees and authorized third parties who access or use NexusTech information and technology resources regardless of location.

It covers:

- Company-provided laptops, desktops and mobile devices and any authorized personal device used to access NexusTech resources.
- Corporate networks and remote-access services.
- Email, messaging and collaboration platforms.
- Business applications and databases.
- Approved cloud services and storage platforms.
- Internet access provided through NexusTech.
- NexusTech information accessed from authorized personal or remote devices.

## 2.4 Policy Statements

### 2.4.1 Acceptable Use

NexusTech information and technology resources shall primarily be used for authorized business activities.

Users must:

- Use NexusTech systems, applications and information only for authorized purposes related to their assigned responsibilities.
- Protect their authentication credentials and must not disclose passwords or share accounts with another person.
- Use multi-factor authentication where required by NexusTech.
- Access only information, applications and systems for which they have been authorized.
- Apply security updates and patches when prompted and must not disable, bypass or interfere with endpoint security controls (e.g., antivirus, MFA).
- Protect company and client information from unauthorized access, disclosure, alteration, loss or destruction.
- Store and share NexusTech information only through approved systems, applications and cloud services.
- Lock or log off unattended devices and report lost or stolen devices to IT/Security immediately.
- Promptly report suspected malware, phishing, unauthorized access, data loss or other suspected security incidents to the IT Helpdesk or Information Security team.

### 2.4.2 Reasonable Personal Use

Limited, incidental personal use of NexusTech information technology resources is permitted provided that such use:

- Is occasional and reasonable, and does not interfere with the employee's duties or productivity.
- Does not create material additional costs for NexusTech or consume excessive network, storage or computing resources.
- Does not violate this Policy or any other NexusTech requirement, including the prohibited activities in section 2.4.3.
- Does not expose NexusTech systems or information to unnecessary security, legal, financial, reputational or compliance risk.

NexusTech may restrict or withdraw personal-use privileges where their use creates operational, security, legal or compliance concerns.

### 2.4.3 Prohibited Activities

Users must not:

- Install or download unauthorized software, browser extensions, applications, hardware or other executable content on NexusTech devices without IT/Security approval.
- Disable, bypass, remove or interfere with security controls such as antivirus software, endpoint protection, encryption, firewalls or multi-factor authentication.
- Share user accounts, passwords or authentication tokens with another person.
- Attempt to access systems, files, accounts or information for which they have not been authorized.
- Transmit, store or process NexusTech or client data using personal cloud storage, personal email or unauthorized messaging applications.
- Connect to NexusTech networks or resources over unsecured public Wi‑Fi without using the company-approved VPN or connect unauthorized devices to the corporate network where approval is required.
- Use NexusTech systems to conduct unlawful, fraudulent, abusive or malicious activities, including harassment, discrimination, defamation or the transmission of unlawful, offensive or discriminatory material.
- Introduce malware or intentionally execute malicious code on NexusTech systems.
- Use NexusTech systems for unauthorized commercial activity, cryptocurrency mining, or any activity that violates software licensing or intellectual property rights.
- Use NexusTech resources to conduct unauthorized security testing, scanning, exploitation or attempts to circumvent security controls.
- Copy, disclose or transmit confidential company or client information to unauthorized internal or external parties.
- Use NexusTech technology resources in a manner that materially interferes with business operations, system performance or other users' ability to perform their duties.

## 2.5 Roles and Responsibilities

| Role | Responsibilities |
|------|------------------|
| Users | Read, understand and comply with the AUP; protect credentials and devices; use only authorized systems and services; complete required security awareness training; and promptly report suspected incidents or policy violations. |
| Managers | Ensure personnel under their supervision understand the Policy, promote compliance, approve legitimate business exceptions in coordination with Information Security and escalate identified or repeated violations through the appropriate channels. |
| IT / Information Security | Own, maintain and enforce this Policy, implement and maintain appropriate technical security controls, monitor compliance where authorized, investigate suspected security events, provide guidance to users and maintain supporting standards and procedures. |
| Information Security Manager | Own and maintain the AUP, oversee its implementation, assess security-related exceptions, monitor effectiveness and coordinate periodic reviews. |
| Human Resources (HR) | Support communication and awareness, maintain applicable employee acknowledgement records, and support or coordinate disciplinary processes arising from confirmed violations, in coordination with IT/Security and management. |
| CEO / Senior Management | Approve the Policy, provide visible management support and ensure appropriate organizational resources are available for implementation. |
