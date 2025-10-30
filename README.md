# Secure Cloud Identity 

## Project Overview
This project demonstrates an **enterprise-grade Microsoft 365 & Intune deployment** for a 50-user simulated company.  
It showcases modern identity, device, and security management, following best practices for pilot deployment, security baselines, Conditional Access, and monitoring.

**Architecture**
- Entra ID for identity management and Conditional Access
- Intune for endpoint security and compliance
- Azure Log Analytics + Sentinel for monitoring
- Power Automate for stale device automation

**Key Outcomes**
- 7 devices enrolled (Windows 11 & iOS)
- Conditional Access blocking 4 non-US attempts
- 100% MFA and SSPR registration compliance
- All corporate devices encrypted with BitLocker

---

## Table of Contents

| Phase | Description | Folder |
|-------|-------------|--------|
| 0 | Groups & Tenant Setup | [01_Groups_&_TenantSetup](01_Groups_&_TenantSetup/README.md) |
| 1 | Tenant Prep & Licensing | [02_Tenant_Licensing](02_Tenant_Licensing/README.md) |
| 2 | Intune MDM Automatic Enrollment | [03_Intune_Enrollment](03_Intune_Enrollment/README.md) |
| 3 | Windows 11 Enrollment | [04_Win11_Enrollment](04_Win11_Enrollment/README.md) |
| 4 | iPhone BYOD & MAM | [05_iOS_MAM](05_iOS_MAM/README.md) |
| 5 | Security Baselines & Hardening | [06_Security_Baseline](06_Security_Baseline/README.md) |
| 6 | Conditional Access | [07_ConditionalAccess](07_ConditionalAccess/README.md) |
| 7 | MFA & SSPR | [08_MFA_SSPR](08_MFA_SSPR/README.md) |
| 8 | Device Lifecycle & Runbooks | [09_Runbooks_Automation](09_Runbooks_Automation/README.md) |
| 9 | Monitoring & SOC Reporting | [10_Monitoring_Sentinel](10_Monitoring_Sentinel/README.md) |
| 10 | Pilot Results & Portfolio | [11_Pilot_Results](11_Pilot_Results/README.md) |

---

## Technologies Used
- Microsoft Entra ID
- Microsoft Intune
- Microsoft 365 E5
- Azure Monitor & Sentinel
- Power Automate
- BitLocker
- iOS MAM (App Protection Policy)

## Skills Demonstrated
- Zero Trust Security Architecture  
- Endpoint & Mobile Device Management  
- Conditional Access & MFA Design  
- Azure Monitoring and Log Analytics  
- Automation via Power Automate  
- Runbook Documentation & Reporting

