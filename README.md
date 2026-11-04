<div align="center">



<!-- Animated Bratz-Palette Gradient Header Banner -->

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving\&color=0:64382E,25:97524B,50:8B3B62,75:82559F,100:694668\&height=200\&section=header\&text=Bratz.lab%20IAM%20Infrastructure\&fontSize=42\&fontColor=ffffff\&animation=fadeIn\&fontAlignY=35\&desc=Enterprise%20Hybrid%20Identity%20%26%20Access%20Management%20Portfolio\&descAlignY=58\&descSize=18" alt="Bratz.lab Banner"/>



<!-- Custom Bratz Color Theme Tech Badges -->

!\[Windows Server 2022](https://img.shields.io/badge/Windows\_Server\_2022-64382E?style=for-the-badge\&logo=windows\&logoColor=white)

!\[Active Directory](https://img.shields.io/badge/Active\_Directory-97524B?style=for-the-badge\&logo=microsoft\&logoColor=white)

!\[Microsoft Entra ID](https://img.shields.io/badge/Microsoft\_Entra\_ID-8B3B62?style=for-the-badge\&logo=microsoft-azure\&logoColor=white)

!\[PowerShell](https://img.shields.io/badge/PowerShell-82559F?style=for-the-badge\&logo=powershell\&logoColor=white)

!\[VMware Workstation](https://img.shields.io/badge/VMware\_Workstation\_Pro-694668?style=for-the-badge\&logo=vmware\&logoColor=white)



</div>



\---



\## 📌 Project Overview

An end-to-end enterprise Identity and Access Management (IAM) homelab simulating a hybrid corporate environment (`Bratz.lab`). Built to mirror real-world identity engineering workflows, this project demonstrates structured Active Directory architecture, automated lifecycle provisioning via PowerShell, least-privilege network file share governance, and hybrid cloud synchronization with Microsoft Entra ID.



\---



\## 🗺️ Architecture \& Topology

\* \*\*Hypervisor:\*\* VMware Workstation Pro

\* \*\*Domain Controller:\*\* Windows Server 2022 (`Bratz.lab`)

\* \*\*Directory Structure:\*\* Dedicated Organizational Units (`Bratz\_users`) with departmental security groups

\* \*\*Cloud Identity:\*\* Microsoft Entra ID linked via Microsoft Entra Connect



\*(Architecture diagram coming soon)\*



\---



\## 🛠️ Lab Phases \& Documentation



| Phase | Focus Area | Key Technologies \& Deliverables |

| :--- | :--- | :--- |

| \[!\[](https://img.shields.io/badge/Phase\_01-64382E?style=flat-square)](./01-Infrastructure-Setup/) | \*\*Virtual Infrastructure \& DC Promo\*\* | VMware Workstation Pro, Windows Server 2022, AD DS, DNS |

| \[!\[](https://img.shields.io/badge/Phase\_02-97524B?style=flat-square)](./02-Active-Directory-Design/) | \*\*Organizational Unit \& Group Design\*\* | Tiered OU structure (`Bratz\_users`), Security Groups |

| \[!\[](https://img.shields.io/badge/Phase\_03-8B3B62?style=flat-square)](./03-Identity-Provisioning/) | \*\*Automated Lifecycle Provisioning\*\* | PowerShell bulk user creation (20 users), attribute population |

| \[!\[](https://img.shields.io/badge/Phase\_04-82559F?style=flat-square)](./04-File-Services-And-Permissions/) | \*\*Role-Based Access Control (RBAC)\*\* | Departmental file shares, NTFS vs. Share permissions |

| \[!\[](https://img.shields.io/badge/Phase\_05-694668?style=flat-square)](./05-Hybrid-Identity-Entra-Connect/) | \*\*Hybrid Identity Synchronization\*\* | Microsoft Entra Connect, custom UPNs, Cloud Sync Verification |



\---



\## 💻 Key Capabilities Demonstrated

\* \*\*Directory Architecture:\*\* Engineered a scalable OU structure and security group hierarchy following least-privilege principles.

\* \*\*IAM Automation:\*\* Developed PowerShell scripts to automate user provisioning, attribute standardization, and group memberships.

\* \*\*Access Governance:\*\* Configured departmental network shares mapped to role-based security groups.

\* \*\*Hybrid Cloud IAM:\*\* Implemented and validated identity synchronization between on-premises Active Directory and Microsoft Entra ID.



<!-- Matching Bratz-Palette Footer Wave -->

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving\&color=0:694668,25:82559F,50:8B3B62,75:97524B,100:64382E\&height=110\&section=footer" alt="Footer"/>

