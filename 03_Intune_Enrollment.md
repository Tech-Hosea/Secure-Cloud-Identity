# Phase 2 — Intune MDM Automatic Enrollment

## Objective
Configure automatic enrollment scope, enrollment restrictions, and Autopilot basics.

## Screenshots
1. **MDM User Scope**
<img width="821" height="334" alt="MDM User Scope" src="https://github.com/user-attachments/assets/5e139b83-6b26-4143-b40b-07db83408be4" />

 “Scoped automatic enrollment to pilot Intune users.”

2. **Enrollment Restrictions**
  <img width="538" height="331" alt="Enrollment Restriction" src="https://github.com/user-attachments/assets/956fc9de-5de9-4d52-bbab-a58e8be707e1" />
 
    “Defined platform restrictions to prevent unsupported devices from enrolling.”

## Notes
- MDM scope: `GRP_Pilot_Intune_Users`
- Enrollment restrictions: block legacy Android, unsupported OS

## Test Steps
- Add user to pilot group → confirm auto-enrollment in Company Portal
