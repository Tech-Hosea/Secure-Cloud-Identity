# Phase 1 — Tenant Prep & Licensing

## Objective
Assign licenses, verify domains, and configure break-glass hygiene.

## Screenshots
1. **License Assignment**
  <img width="641" height="326" alt="License Assignment" src="https://github.com/user-attachments/assets/5f1df7a5-9e35-4ab3-94eb-d35d67000251" />
 
   *Caption:* “Assigned Microsoft 365 E5 license to pilot user.”

2. **Break-Glass Account**
<img width="640" height="324" alt="Break-glass Account" src="https://github.com/user-attachments/assets/b5eec0ed-ff12-4eea-90aa-acc32bfafa97" />
   
   *Caption:* “Configured emergency admin account with minimal privileges.”

## Notes
- Pilot user: `your.pilotuser@something.onmicrosoft.com` assigned E5
- Break-glass user: `Yourbreakglassuser@something.onmicrosoft.com` stripped of non-essential licenses

## Test Steps
- Attempt Windows 11 device enrollment for licensed user
- Confirm break-glass cannot enroll but account is enabled
