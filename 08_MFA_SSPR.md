# Phase 7 — MFA & SSPR

## Objective
Enable Self-Service Password Reset (SSPR) and staged MFA with phishing-resistant methods.

## Screenshots
1. **SSPR Settings**
<img width="613" height="335" alt="SSPR Setting" src="https://github.com/user-attachments/assets/37af22f9-890e-43d2-997e-d8134d89035f" />

   *Caption:* “Enabled SSPR for pilot group.”

2. **MFA Conditional Access**
<img width="796" height="410" alt="MFA Conditional Access Policy" src="https://github.com/user-attachments/assets/3452a53d-ea6a-49f9-9575-87647c2b7ac7" />

   *Caption:* “Staged MFA policy configured in report-only mode.”

3. **Registration Prompt**

   *Caption:* “Pilot user prompted to register Authenticator app.”

## Notes
- Pilot users must register two methods: Authenticator + phone
- SMS disabled to enforce phishing-resistant MFA

## Test Steps
- Reset password → confirm SSPR prompts
- Sign-in → confirm MFA registration
