# ServiceNow IAM Access Request Workflow

## Overview
Built a ServiceNow IAM access request and incident workflow to simulate enterprise identity governance, privileged access management, and IAM operational support processes.

This lab demonstrates how access requests can be submitted, reviewed, approved, investigated, and tracked through ServiceNow.

---

## Business Use Case
Organizations need a controlled process for requesting and approving access to systems such as CyberArk, Active Directory, AWS IAM, and Microsoft Entra ID.

This project simulates an IAM workflow where users request access, provide business justification, receive manager approval, and are supported through incident tracking when privileged access issues occur.

---

## Features Implemented
- IAM access request form
- Access type dropdown for CyberArk, AD, AWS IAM, Entra ID, local admin, and read-only access
- Business justification requirement
- Manager approval workflow
- IAM incident ticket creation
- Incident investigation notes
- Ticket lifecycle tracking from New to In Progress
- Least privilege access review process

---

## Workflow
User submits access request  
↓  
Manager approval required  
↓  
IAM team reviews request  
↓  
Access is provisioned based on least privilege  
↓  
Incident created if access fails  
↓  
IAM team investigates and resolves issue  

---

## Screenshots

### Access Request Form
<img src="https://github.com/user-attachments/assets/387742a1-3c99-438f-af79-e34a1d65ef9a" width="900" />


### Approval Workflow
<img src="https://github.com/user-attachments/assets/923b1a6b-d8a0-4b8d-b29e-a6c678878de5" width="900" />


### Incident Created
<img src="https://github.com/user-attachments/assets/ec5b3604-6571-41ab-922e-20de226eda32" width="900" />

### Incident Queue View
<img src="https://github.com/user-attachments/assets/17125e5f-8832-4b2e-ac8a-c786b57b0433"  width="1100" />

### Incident Investigation/ In Progress
<img src="https://github.com/user-attachments/assets/b28bcdd3-46c2-4d22-96cc-0f44f6c1e91d"  width="1100" />

### Incident Resolved
<img src="https://github.com/user-attachments/assets/0e433509-5e79-40fa-b9d8-840e34cd13b4"  width="1100" />


---

## Security Concepts Demonstrated
- Identity and Access Management
- Privileged Access Management
- Least Privilege
- RBAC
- Access Governance
- Approval Workflows
- Incident Management
- SLA Awareness
- IAM Operations

---

## Tools Used
- ServiceNow Creator Studio
- ServiceNow Incident Management
- IAM Access Request Workflow
- CyberArk / PAM concepts
- Active Directory concepts
- AWS IAM concepts
- Microsoft Entra ID concepts

## Workflow Diagram
<img src="https://github.com/user-attachments/assets/188f7fd2-56b8-46f7-ae78-294b670198b8"  width="1000" />


---

## Outcome
Designed a practical IAM access request and incident workflow that demonstrates how enterprise teams manage access approvals, privileged access issues, and IAM support processes through ServiceNow.
