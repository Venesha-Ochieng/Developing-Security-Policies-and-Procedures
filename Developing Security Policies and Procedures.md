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
