#  Azure Virtual Desktop (AVD) Environment for Development Team
This project aims to design and implement a secure, scalable **Virtual Desktop Infrastructure** (VDI) using Azure Virtual Desktop (AVD) for an application development team of 60 users. The solution provides:

* 10 Personal VMs for dedicated developers.
* Pooled VMs for 50 users to optimize resource utilization.

### Key Objectives

Deliver a centralized virtual workspace for developers.
Ensure application management via Microsoft Intune.
Provide profile management using ProfileUnity with FSLogix containers.
Implement secure access with Azure AD Conditional Access and MFA.
Enable Disaster Recovery (DR) and backup strategy for business continuity.


### Core Components

Azure Virtual Desktop (AVD): Host pools for personal and pooled VMs.
Microsoft Intune: Application deployment and compliance.
ProfileUnity: Profile and persona management.
Azure AD: Identity and access control.
Azure Files Premium: Profile storage and golden images.
Azure Firewall & Secure Gateway: Network security.
Azure Site Recovery: DR and failover strategy.

### Benefits

Centralized management of applications and profiles.
Secure and compliant environment for developers.
High availability and disaster recovery readiness.
Scalable design for future growth.

<img width="975" height="650" alt="image" src="https://github.com/user-attachments/assets/beff8139-b1e0-4076-9041-45d21902a9a1" />
