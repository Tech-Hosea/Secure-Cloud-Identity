# Phase 0 — Groups & Tenant Setup

## Objective
Create enterprise-grade security groups and prepare tenant for staged pilot testing.

## Screenshots
1. **Group List**
<img width="537" height="332" alt="Group LIst" src="https://github.com/user-attachments/assets/55873b46-9fc3-4156-9d27-bae55f1e03d6" />

   *Caption:* “Created structured security groups for pilot testing and role-based policy assignment.”

2. **Group Members**
<img width="664" height="248" alt="Group Members" src="https://github.com/user-attachments/assets/1e34f3f9-c8ff-4e3c-8d01-adc0de33b177" />

   *Caption:* “Pilot Intune group containing test users with assigned licenses.”

## Notes
- Groups created:
  - `GRP_Pilot_Intune_Users`
  - `GRP_Corp_Win11`
  - `GRP_BYOD_Mobiles`
  - `GRP_MFA_Required`
  - `GRP_BreakGlass_Admins`
- Membership type: Assigned
- Admin user: `youradmin@something.onmicrosoft.com` added to break-glass group

## Test Steps
- Create temporary user and add to `GRP_Pilot_Intune_Users`
- Confirm membership propagation in portal

