<div align="center">
  <img width="100%" src="./assets/banner.svg" alt="Bratz.lab Banner"/>
  <br/>
  <img src="https://img.shields.io/badge/Windows_Server_2022-64382E?style=for-the-badge&logo=windows&logoColor=white" alt="Windows Server 2022"/>
  <img src="https://img.shields.io/badge/Active_Directory-97524B?style=for-the-badge&logo=microsoft&logoColor=white" alt="Active Directory"/>
  <img src="https://img.shields.io/badge/Microsoft_Entra_ID-8B3B62?style=for-the-badge&logo=microsoftazure&logoColor=white" alt="Microsoft Entra ID"/>
  <img src="https://img.shields.io/badge/PowerShell-82559F?style=for-the-badge&logo=powershell&logoColor=white" alt="PowerShell"/>
  <img src="https://img.shields.io/badge/VMware_Workstation_Pro-694668?style=for-the-badge&logo=vmware&logoColor=white" alt="VMware Workstation"/>
</div>

<br/>

## Project Overview

An end-to-end enterprise Identity and Access Management (IAM) homelab simulating a hybrid corporate environment (`Bratz.lab`). Built to mirror real-world identity engineering workflows, this project demonstrates structured Active Directory architecture, automated lifecycle provisioning via PowerShell, least-privilege network file share governance, and hybrid cloud synchronization with Microsoft Entra ID.

---

## Architecture & Topology

* **Hypervisor:** VMware Workstation Pro
* **Domain Controller:** Windows Server 2022 (`bratz.lab`)
* **Directory Structure:** Dedicated Organizational Units (`Bratz_users`, `Bratz_Groups`) with departmental security groups
* **Cloud Identity:** Microsoft Entra ID linked via Microsoft Entra Connect

*(Architecture diagram coming soon)*

---

## Lab Phases & Documentation

| Phase | Focus Area | Key Technologies & Deliverables |
| :--- | :--- | :--- |
| <a href="./01-Infrastructure-Setup/"><img src="https://img.shields.io/badge/Phase_01-64382E?style=flat-square" alt="Phase 01"/></a> | **Virtual Infrastructure & DC Promo** | VMware Workstation Pro, Windows Server 2022, AD DS, DNS |
| <a href="./02-Active-Directory-Design/"><img src="https://img.shields.io/badge/Phase_02-97524B?style=flat-square" alt="Phase 02"/></a> | **Organizational Unit & Group Design** | Tiered OU structure (`Bratz_users`, `Bratz_Groups`), Security Groups |
| <a href="./03-Identity-Provisioning/"><img src="https://img.shields.io/badge/Phase_03-8B3B62?style=flat-square" alt="Phase 03"/></a> | **Automated Lifecycle Provisioning** | PowerShell bulk user creation (20 users), attribute population |
| <a href="./04-File-Services-And-Permissions/"><img src="https://img.shields.io/badge/Phase_04-82559F?style=flat-square" alt="Phase 04"/></a> | **Role-Based Access Control (RBAC)** | Departmental file shares, NTFS vs. Share permissions |
| <a href="./05-Hybrid-Identity-Entra-Connect/"><img src="https://img.shields.io/badge/Phase_05-694668?style=flat-square" alt="Phase 05"/></a> | **Hybrid Identity Synchronization** | Microsoft Entra Connect, custom UPNs, Cloud Sync Verification |

---

## Key Capabilities Demonstrated

* **Directory Architecture:** Engineered a scalable OU structure and security group hierarchy following least-privilege principles.
* **IAM Automation:** Developed PowerShell scripts to automate user provisioning, attribute standardization, and group memberships.
* **Access Governance:** Configured departmental network shares mapped to role-based security groups.
* **Hybrid Cloud IAM:** Implemented and validated identity synchronization between on-premises Active Directory and Microsoft Entra ID.