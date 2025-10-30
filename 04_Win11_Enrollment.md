# Phase 3 — Windows 11 Enrollment

## Objective
Enroll Windows 11 laptop via Company Portal and Autopilot; escrow BitLocker keys.

## Screenshots
1. **Device Record in Intune**
<img width="793" height="182" alt="Device Record" src="https://github.com/user-attachments/assets/71784113-c605-415f-9d44-5f912eeabb74" />

   *Caption:* “Windows 11 laptop enrolled in Intune with correct ownership.”

2. **BitLocker Escrow**
<img width="486" height="343" alt="BitLocker Escrow" src="https://github.com/user-attachments/assets/cca904c2-5879-45d4-bdce-6f8dd75026ed" />


3. **Company Portal Verification**

![Company Portal](https://github.com/user-attachments/assets/b4db092f-b5bd-4dd7-8676-96e680f47b5e)

   *Caption:* “Company Portal confirms device is managed.”

## Notes
- TPM 2.0 required
- BitLocker enforced with XTS-AES 256 encryption

## Test Steps
- Confirm device appears in Endpoint Manager → Devices
- Verify BitLocker recovery key visibility in Azure AD
