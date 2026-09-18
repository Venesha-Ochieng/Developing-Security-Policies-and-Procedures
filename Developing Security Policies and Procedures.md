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

## 2.6 Compliance and Enforcement

Compliance with this Policy is mandatory for all persons within its scope.

Suspected violations shall be reviewed through the appropriate NexusTech management, Information Security and/or HR processes. Depending on the nature and severity of the violation, appropriate action may include:

- Security guidance or retraining.
- Restriction or suspension of system access.
- Removal of unauthorized applications or services.
- Formal disciplinary action in accordance with applicable organizational processes, up to and including termination of employment or contract.
- Contractual action for contractors or third parties.
- Escalation to law enforcement or other authorities where unlawful activity is involved, or where otherwise required by applicable legal, regulatory or contractual obligations.

HR and the employee's manager will be involved in any disciplinary process arising from a confirmed violation. Enforcement should be consistent and proportionate to the nature, severity and recurrence of the violation.

## 2.7 Exceptions

Exceptions to this Policy must not be granted informally.

Where a legitimate business requirement prevents compliance, the requesting employee's manager must submit a documented exception request to the Information Security Manager describing the:

**Business justification → affected policy requirement → risk → proposed compensating controls → requested duration.**

The Information Security Manager shall assess the security risk associated with the request. Where necessary, the relevant system owner, business owner or management authority shall participate in the assessment and approval.

Approved exceptions must:

- Be formally approved before the deviation begins.
- Include appropriate compensating controls where required.
- Have a defined owner.
- Have an expiry or review date and be subject to periodic review.
- Be recorded in the organization’s exception register.

Unapproved deviations are treated as violations. Expired exceptions must either be closed, renewed through a new assessment or brought back into compliance.

## 2.8 Approval

| Approval Field | Details |
|---------------|---------|
| Policy Owner | Information Security Manager |
| Approval Authority | Marcus Vance, Chief Executive Officer |
| Version | 1.0 |
| Effective Date | 18 September 2026 |
| Next Review Date | 18 September 2027 |

- Approved by: Marcus Vance, Chief Executive Officer — Date: _______________

# Task 3 Create an Actionable User Access Request Procedure

The new policy framework requires all access to NexusTech systems to be formally requested, approved and provisioned. The Helpdesk currently acts on informal emails and chat messages, creating inconsistent permissions and unauthorised access risk.

Develop a step-by-step User Access Request Procedure that a Helpdesk technician can follow consistently.

## 3.1 Purpose and scope

This procedure defines the steps a Helpdesk technician must follow to request, approve, provision, and record access to NexusTech systems, applications, and data. It applies to all new-hire, role-change and ad-hoc access requests involving employees, contractors, and third parties.

## 3.2 Prerequisites, including required systems, approvals and authorised roles

| Prerequisite | Requirement |
|-------------|-------------|
| Required system | Request submitted via an approved NexusTech ticketing/access-management workflow |
| Approval | The request must have approval from the user's authorized manager and, where applicable, the relevant Data/System Owner |
| Authorised roles | Only authorized Helpdesk/IT personnel may create accounts, modify accounts or provision approved access. |

## 3.3 Request intake through an approved ticket or workflow

Requester submits via the approved ticketing/workflow tool. Technician verifies the ticket contains: full name, department/role, manager, target system, requested role/access level, justification, start date, and end date (if temporary). Informal emails, chats, calls or verbal instructions are never actioned; incomplete requests are returned for correction.

## 3.4 Verification of manager/data-owner approval

Technician confirms the manager has approved the business need, role-fit, and appropriateness of the access level.

For sensitive information, restricted applications, databases or other controlled resources, Data/System Owner approval is also required. Missing approvals place the request on hold.

## 3.5 Account creation at a high level

Once approvals are confirmed, an authorized technician checks for an existing account, creates a new one or selects the existing authorized account, applies required account settings, sets start/expiry dates for temporary access and enables required security controls.

## 3.6 Role-based permission assignment and least-privilege checks

Technician assigns permissions matching the approved role/profile, ensuring:

- Access maps to an approved role where available.
- Only permissions necessary for the user's duties are granted.
- No unnecessary admin/privileged access.
- Provisioned access does not exceed what was approved.

Requests exceeding the standard role profile require additional approval before granting. Technician then verifies:

```text
Approved Access
        ↓
Role-Based Permission
        ↓
Least-Privilege Check
        ↓
Provisioned Access
```

Any excess or unauthorised permission is removed before proceeding.

## 3.7 User/manager notification

Technician confirms via notification: system/application, approved access role/level, effective date, expiry date (if applicable), any conditions, and Helpdesk contact for issues. Passwords/credentials are never sent via insecure channels.

## 3.8 Evidence capture and ticket closure

Before closing, technician verifies the ticket contains:

- Original request.
- Justification.
- Manager approval.
- Data/System Owner approval (where applicable).
- Account created/modified.
- Role/permissions assigned.
- Provisioning date/time.
- Responsible technician.
- Least-privilege check evidence.
- User/manager notification.

Ticket is then marked Completed/Closed.

## 3.9 Handling of emergency or exceptional requests

Urgent access needs follow a defined emergency path rather than bypassing approval:

```text
Emergency request
        ↓
Document reason
        ↓
Obtain emergency approval
        ↓
Grant minimum necessary access
        ↓
Set expiry
        ↓
Review
        ↓
Remove or regularize access
```

Technician must:

- Create/obtain an approved emergency ticket.
- Record why normal processing couldn't be followed.
- Obtain approval from an authorized manager or designated authority.
- Grant only minimum necessary access, time-bound where possible.
- Document permissions granted and who authorized them.
- Arrange a post-event review.
- Remove temporary access when no longer needed, or convert to standard access via normal approval.

## 3.10 Record retention and audit trail expectations

Completed requests and evidence are retained in the approved ticketing/identity-management/records repository per NexusTech's applicable retention requirements.

The audit trail must answer:

| Audit Question | Required Evidence |
|----------------|-------------------|
| Who requested access? | Requester/user details |
| Why was it required? | Business justification |
| Who approved it? | Manager and Data/System Owner approval |
| What was approved? | Approved role/permission |
| What was actually granted? | Provisioning record |
| Who granted it? | Technician details |
| When was it granted? | Date/time record |
| Was completion verified? | Verification and closure evidence |

Records must be protected from unauthorized alteration or deletion and remain available for access reviews, investigations and audits.

# Task 4 Policy Implementation and Communication

The AUP and User Access Request Procedure have been approved by the CEO. Your next responsibility is to ensure that employees understand and adopt the requirements. Simply emailing a PDF is not sufficient.

Develop a Communication and Training Plan for the rollout of the new Acceptable Use Policy.

## 4.1 Communication and Training Plan

| Audience | Key Message / Training Content | Channel | Owner | Timing | Acknowledgement | Success Measure |
|-----------|-------------------------------|---------|-------|--------|----------------|----------------|
| All Employees | The new AUP outlines employee responsibilities for acceptable use, prohibited activities, reasonable personal use, credential protection, approved software and cloud services and incident reporting. | All-hands meeting; intranet policy page; mandatory e-learning module | Information Security Manager & HR | Week 1: announcement and publication. Week 2: mandatory training. | Electronic confirmation of having read, understood and agreed to comply with the AUP | ≥95% training completion; ≥95% policy acknowledgement; ≥90% knowledge-check pass rate |
| IT / Helpdesk Staff | Their role in enforcing acceptable use and applying the User Access Request Procedure, ticket intake, approval verification, account creation, role-based permissions, least privilege, evidence capture, closure and emergency requests. | Instructor-led workshop; procedure walkthrough, practical scenarios, Helpdesk quick-reference guide | Information Security Manager & IT Manager | Week 1, before the new procedure goes live | Attendance recorded; scenario-based knowledge check completed | 100% of relevant staff trained before processing requests independently; ≥90% scenario assessment pass rate |
| Managers / Data & System Owners | Management responsibilities for supporting the AUP and approving access legitimate business need, appropriate access levels, least privilege, enforcement and escalation of non-compliance. | Management briefing; email summary; intranet; manager quick-reference guide | Information Security Manager | Week 1, before employee-wide training completes | Electronic acknowledgement of policy and approval responsibilities | 100% of relevant managers briefed; reduction in incomplete/incorrect approvals within first 30 days |
| Contractors / Relevant Third Parties | AUP applies to use of NexusTech devices, systems, networks and information approved systems, credential/information protection, prohibited activities, incident reporting. | Contractor onboarding; policy portal; email; security briefing where appropriate | Contract Owner, HR & Information Security | Before system access is granted, and on material policy changes | Electronic or signed acknowledgement before access is activated | 100% of applicable contractors acknowledge the AUP before receiving access |
| Employees Who Don't Complete Training/Acknowledgement | Reinforce that training and acknowledgement are mandatory; explain the outstanding requirement and deadline. | Automated reminder; direct email; manager follow-up | HR & Information Security Manager | End of Week 2; Week 3 follow-up | Completion and acknowledgement recorded in the approved learning/policy system | Outstanding users reduced to <5%; unresolved cases escalated to the relevant manager |
| Employees Showing Repeated Misunderstanding or Non-Compliance | Targeted clarification/refresher training on misunderstood requirements; repeated or deliberate violations escalated via management, Information Security and HR processes. | Targeted refresher training; one-to-one guidance; manager meeting; HR/Security escalation where appropriate | Information Security Manager, Manager & HR | As identified via knowledge checks, Helpdesk reports, incidents or monitoring | Retraining completion and corrective action documented | Improved knowledge-check results; reduction in repeated violations/misunderstandings |

# Task 5 Policy Review and Maintenance

One year later, NexusTech has migrated its primary database to AWS. A minor security incident also occurred when an employee shared a sensitive document through a personal cloud storage account. These changes require you to determine whether the AUP should be reviewed and updated.

Prepare a Policy Review Memo to the Information Security Steering Committee.

## 5.1 A concise 2–3 paragraph Policy Review Memo to the Information Security Steering Committee

### MEMORANDUM

**To:** Information Security Steering Committee  
**From:** Information Security Manager  
**Date:** 18 September 2027  
**Subject:** Triggered Review of the Acceptable Use Policy (AUP), Version 1.0

Two significant developments require an early review of NexusTech’s Acceptable Use Policy. First, the migration of the company’s primary database to AWS represents a major change to the technology environment and introduces new considerations around how company and client information is accessed, stored and shared in cloud services. Second, a recent incident involving an employee sharing a sensitive document through a personal cloud-storage account indicates a potential weakness in the current acceptable-use requirements or employee understanding of approved file-sharing methods. These events are clear review triggers and justify assessing whether the existing AUP remains suitable for NexusTech’s current operating environment.

The review should involve consultation with Information Security, IT/Cloud Operations, Legal/Compliance, relevant Data and System Owners, HR and affected business units. The review process should include a risk assessment of cloud data handling and file-sharing practices and examination of relevant evidence, including the security incident record, system and access logs, Helpdesk records, policy exceptions and employee training or acknowledgement records. Based on the findings, the AUP should be updated to (1) clearly require company and client information to be stored, processed and shared only through NexusTech-approved cloud services and accounts, explicitly prohibiting personal cloud-storage services for business or sensitive information, and (2) provide clearer requirements for approved external file-sharing methods so employees understand how information can be shared securely when there is a legitimate business need. These changes should also be reinforced through targeted security awareness training.

As the Policy Owner, the Information Security Manager should coordinate the review, stakeholder consultation and preparation of the revised AUP, with the updated version submitted to Marcus Vance, CEO, as the designated Approval Authority. Following approval, the revised policy should be version-controlled, communicated to affected users and supported by updated awareness or training where necessary. The AUP should continue to be formally reviewed annually, with an earlier review initiated following significant technology or cloud changes, material security incidents, major changes in business or client-data requirements, significant audit findings, or recurring policy violations. This approach ensures that the AUP remains relevant as NexusTech’s technology environment and security risks change.

## Suggested Reference Resources

1. GRC102 Week 2 course material: Developing Security Policies and Procedures.
2. ISO/IEC 27001:2022 and ISO/IEC 27002 guidance relevant to information security governance and controls.
3. NIST Cybersecurity Framework (CSF) 2.0.
4. SOC 2 Trust Services Criteria concepts relevant to the scenario.
5. Applicable internal policy-development guidance provided by the instructor.
